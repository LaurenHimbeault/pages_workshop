## **Step 4: Running Jekyll Locally**

### **Why Run Jekyll Locally?**
Running Jekyll locally lets you see your changes before making them live.

### **Instructions**
1. **Navigate to the cloned repository:**
   ```sh
   cd USERNAME.github.io
   ```
2. **Start the local Jekyll server:**
   ```sh
   bundle exec jekyll serve
   ```
3. **Preview your site:**
   - Open a browser and go to:
     ```
     http://127.0.0.1:4000
     ```
   - Any changes you make will refresh automatically.

### **Common Issues & Fixes**
| Issue | Solution |
|-------|----------|
| `jekyll: command not found` | Run `gem install bundler jekyll` |
| Permission denied | Use `sudo gem install bundler jekyll` (Mac/Linux) |
| Site not updating | Restart server with `CTRL+C`, then `bundle exec jekyll serve` |

**Next Step: Customizing Your Website**

