# Contributing to DWUI

First off, thank you for considering contributing to DWUI! It's people like you that make DWUI such a great tool.

## 🌟 Ways to Contribute

- 🐛 Report bugs
- 💡 Suggest new features
- 📝 Improve documentation
- 🎨 Contribute code
- 🧪 Write tests

## 🚀 Getting Started

### 1. Fork & Clone

```bash
# Fork the repo on GitHub, then clone your fork
git clone https://github.com/YOUR-USERNAME/dwui-new-tab.git
cd dwui-new-tab

# Add the original repo as upstream
git remote add upstream https://github.com/mohammadumar-dev/dwui-new-tab.git
```

### 2. Set Up Development Environment

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

### 3. Create a Branch

```bash
# Create a new branch for your feature
git checkout -b feature/your-feature-name
```

## 📋 Development Guidelines

### Code Style

- Use **TypeScript** for all new files
- Follow existing code formatting
- Use meaningful variable and function names
- Add comments for complex logic

### Component Guidelines

```tsx
// ✅ Good: Descriptive component with props interface
interface ButtonProps {
  label: string;
  onClick: () => void;
}

export function CustomButton({ label, onClick }: ButtonProps) {
  return <button onClick={onClick}>{label}</button>;
}

// ❌ Avoid: Unclear naming and no types
export function Btn(props: any) {
  return <button onClick={props.fn}>{props.txt}</button>;
}
```

### Commit Messages

Use clear, descriptive commit messages:

```bash
# Good
git commit -m "Add dark mode toggle to sidebar"
git commit -m "Fix search bar focus issue on mobile"
git commit -m "Update Aurora animation performance"

# Avoid
git commit -m "fixed stuff"
git commit -m "updates"
```

## 🧪 Testing Your Changes

1. **Build the extension**
   ```bash
   npm run build
   ```

2. **Test in Chrome**
   - Go to `chrome://extensions/`
   - Enable Developer mode
   - Click "Load unpacked"
   - Select the `dist` folder
   - Test all features thoroughly

3. **Check for errors**
   - Open DevTools (F12)
   - Check Console for errors
   - Test on different screen sizes

## 📤 Submitting Changes

### Before Submitting

- [ ] Code follows the project's style
- [ ] Changes have been tested in Chrome
- [ ] No console errors
- [ ] README updated (if needed)
- [ ] Comments added for complex code

### Creating a Pull Request

1. **Push your changes**
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Open a Pull Request**
   - Go to your fork on GitHub
   - Click "Pull Request"
   - Select your branch
   - Fill in the PR template

3. **PR Description should include:**
   - What changes were made
   - Why these changes are needed
   - Screenshots (for UI changes)
   - Any breaking changes

### PR Template

```markdown
## Description
Brief description of what this PR does

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement

## Screenshots (if applicable)
[Add screenshots here]

## Checklist
- [ ] My code follows the style guidelines
- [ ] I have tested my changes
- [ ] I have added necessary comments
- [ ] My changes generate no new warnings
```

## 🐛 Reporting Bugs

### Before Reporting

- Check if the bug has already been reported
- Make sure you're using the latest version
- Try to reproduce the bug consistently

### Bug Report Template

```markdown
**Describe the bug**
A clear description of what the bug is

**To Reproduce**
Steps to reproduce:
1. Go to '...'
2. Click on '...'
3. See error

**Expected behavior**
What you expected to happen

**Screenshots**
If applicable, add screenshots

**Environment:**
- Chrome Version: [e.g. 120.0.6099.109]
- OS: [e.g. Windows 11, macOS 14]
- Extension Version: [e.g. 1.0.0]
```

## 💡 Suggesting Features

We love feature suggestions! Please provide:

1. **Clear description** of the feature
2. **Use case** - why is it needed?
3. **Mockups or examples** (if possible)
4. **Technical considerations** (if you have ideas)

## 📜 Code of Conduct

### Our Standards

- Be respectful and inclusive
- Accept constructive criticism gracefully
- Focus on what's best for the community
- Show empathy towards others

### Unacceptable Behavior

- Harassment or discriminatory language
- Trolling or insulting comments
- Publishing others' private information
- Unprofessional conduct

## ❓ Questions?

- Open a [GitHub Issue](https://github.com/mohammadumar-dev/dwui-new-tab/issues)
- Join discussions in existing issues
- Check existing documentation

## 🙏 Thank You!

Your contributions make DWUI better for everyone. We appreciate your time and effort!

---

Happy Coding! 🚀
