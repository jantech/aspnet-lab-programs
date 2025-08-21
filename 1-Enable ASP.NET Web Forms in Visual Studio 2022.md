# **Enable ASP.NET Web Forms in Visual Studio 2022**

## **ASP.NET Web Forms** is a **legacy framework** (not part of .NET Core / .NET 5+), it’s still supported but only under **.NET Framework (4.x)** inside Visual Studio 2022. By default, Web Forms templates may not appear unless you install the right workloads.


# 🔹 Steps to Enable ASP.NET Web Forms in Visual Studio 2022

### 1. **Install .NET Framework 4.x SDK + Web Development Tools**

1. Open **Visual Studio Installer**.
2. Select **Modify** on your installed Visual Studio 2022.
3. Under **Workloads**, check:

   * ✅ **ASP.NET and web development**
   * ✅ **.NET Framework 4.x development tools** (important for Web Forms)
4. Under **Individual Components** (if needed), ensure:

   * **.NET Framework 4.8 SDK**
   * **.NET Framework 4.8 targeting pack**
   * **Web Deploy**
5. Click **Modify** to install.

---

### 2. **Create a Web Forms Project**

1. Open **Visual Studio 2022**.
2. Go to **File → New → Project**.
3. In the search box, type:

   * `ASP.NET Web Application (.NET Framework)`
4. Select it, then **Next**.
5. Choose:

   * **Project Name & Location**
   * **Framework version** → (e.g., .NET Framework 4.7.2 or 4.8).
6. In the next dialog, pick **Web Forms** template.
7. Finish → Visual Studio will scaffold a Web Forms project with `.aspx` pages.

---

### 3. **Verify Web Forms is Working**

* You’ll see files like `Default.aspx`, `Site.Master`, and `Web.config`.
* Run with **IIS Express** (`Ctrl+F5`).
* A default Web Forms site should launch in your browser.

---
