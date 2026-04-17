# Align CSS, JS, Python Lesson Designs
Approved plan: Standardize to unified template matching styles.css patterns.

## Steps to Complete:

### 1. Update CSS [DONE]
- [x] Added styles to learner/css/styles.css for .content-section, .navigation-buttons, .btn*, .lesson-badge variants, .main-header alias, code blocks
  * .content-section
  * .navigation-buttons 
  * .btn, .btn-primary, .btn-secondary (map to nav-btn)
  * .lesson-badge (base + .beginner/.intermediate mods)
  * .main-header → alias .header
  * Ensure .nav-buttons/.nav-btn.prev/.next works
  * .code-block/.code-explanation enhancements

### 2. Create Template [DONE]
- [x] Created learner/template.html as unified template
- [ ] Test template with live-server
- [ ] Test template with live-server

### 3. Refactor Courses [PENDING]
- [ ] CSS course: Edit all 12 lesson*.html
- [ ] JS course: Edit all 15 lesson*.html  
- [ ] Python course: Edit all 15 lesson*.html
- Use edit_file for exact class/structure replacements

### 4. Test & Validate [PENDING]
- [ ] Preview: npx live-server learner/courses/css/
- [ ] Check consistency across courses
- [ ] Validate no content loss

### 5. Complete
- [ ] attempt_completion

Next action: Update styles.css
