# Keeper Password Manager – Manual E2E Testing

End-to-end **manual testing** of the Keeper Password Manager browser extension.
This project covers **UI, API, authentication, security, and system-level testing**.
Automation testing is intentionally excluded.

---

## 🔍 Testing Coverage

### Extension & UI
- Extension installation & permissions
- UI validation (labels, errors, tooltips)
- User experience and usability checks

### Authentication & Authorization
- Sign up & login flow
- Invalid credential handling
- Master password validation
- Session timeout & auto-lock
- Logout behavior
- Token/session invalidation (manual verification)

### Vault Management
- Add, edit, delete credentials
- Folder creation & organization
- Search and filtering
- Data persistence after refresh / restart

### Autofill & Browser Behavior
- Website login detection
- Autofill accuracy
- Multiple account handling
- Manual vs auto-fill behavior

### Password Generator
- Password strength rules
- Customization options
- Saving generated passwords

### API Testing (Manual)
- Authentication-related API behavior
- Vault data API verification (via browser dev tools)
- Request/response validation
- Error handling and status codes
- Token usage observation

### Security Testing (Manual)
- Vault lock after inactivity
- Clipboard timeout behavior
- Data visibility after logout
- Unauthorized access attempts
- Network interruption scenarios

### Negative & Edge Cases
- Invalid input handling
- Network failure
- Unexpected user actions
- Browser restart scenarios

---

## 🧪 Testing Type

- Manual Testing
- End-to-End (E2E) Testing
- Functional Testing
- API Testing (Manual)
- Authentication & Authorization Testing
- Security Testing
- Regression Testing

> ❌ Automation testing is not included in this project.

---

## 🌐 Application Under Test

- Product: Keeper Password Manager
- Platform: Browser Extension (Chrome)
