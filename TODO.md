# Task: Update Especialidades Z2 Project Files
Approved plan: Security/UX fixes, extract CSS, add cert download, etc.

## Update Plan Steps
- [x] Step 1: Create style.css with common styles extracted from all HTML files
- [x] Step 2: Update index.html - link style.css, hash passwords, add sanitization/loading/errors
- [x] Step 3: Update panel_principal.html - link style.css, fix userAttempts bug, fix syntax errors
- [x] Step 3: Update panel_principal.html - fix renderExams syntax and UI conflicts
- [x] Step 4: Fix Database RLS - Add policies for user insertion and selection
- [x] Step 4: Update certificados.html - link style.css, fix Supabase initialization
- [x] Step 5: Fix Login UI "altered" state in style.css
- [x] Step 5: Fix Database Schema - Add 'logo', 'maxAttempts' and 'active' columns to exams table
- [x] Step 6: Test full flow (login/exam/cert) - Verified
- [x] Step 7: Complete updates - Admin access fixed (Plain text vs Hash mismatch resolved)
- [x] Step 8: Rename folder 'Certificados' to 'diplomas' and update UI labels
- [x] Step 9: Final deployment and folder case-sensitivity fix
- [x] Step 10: Robust image fallback chain and historial UI improvements
- [x] Step 11: Verify GitHub physical file existence and case naming

## Previous Tasks
### Task: Fix 404 error for zona2.png image
- [x] Analyze files and confirm root cause (index.html path mismatch)
- [x] Edit index.html to correct image src from "fondo/zona2.png" to "Fondo/zona2.png"
- [x] Verify fix and complete task

**Current Progress**: Deployment finalized. Project live and functional on GitHub Pages.
