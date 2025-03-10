## **Step 3: Setting Up Jekyll Locally**

### **What is Jekyll?**
Jekyll is a static site generator that lets you preview changes locally before pushing them live.

### **Checking If Jekyll is Installed**
#### **A. Check Ruby Installation**
1. Open Terminal/Git Bash.
2. Type:
   ```sh
   ruby -v
   ```
3. If installed, it will show a version number.
4. If not, install Ruby:
   - **Mac:**
     ```sh
     brew install ruby
     ```
   - **Windows:** Download & install [Ruby](https://rubyinstaller.org/).

#### **B. Install Jekyll & Bundler**
1. Check if Jekyll is installed:
   ```sh
   jekyll -v
   ```
2. If not, install:
   ```sh
   gem install bundler jekyll
   ```
3. Install dependencies in the project folder:
   ```sh
   bundle install
   ```

