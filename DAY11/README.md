/* Base styles */
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background-color: #fafafa;
  color: #333;
  line-height: 1.6;
}

h1 {
  font-size: 2rem;
  margin-top: 1rem;
}

p {
  font-size: 1rem;
  letter-spacing: 0.5px;
}

/* Sidebar toggle */
#menu-toggle {
  display: none;
}

.menu-icon {
  font-size: 1.8rem;
  padding: 1rem;
  display: inline-block;
  cursor: pointer;
}

/* Sidebar styles */
.sidebar {
  position: fixed;
  top: 0;
  left: -250px;
  width: 200px;
  height: 100%;
  background-color: #fff;
  box-shadow: 2px 0 10px rgba(0,0,0,0.1);
  padding-top: 3rem;
  transition: left 0.3s ease-in-out;
}

.menu-item {
  padding: 1rem;
  border-bottom: 1px solid #eee;
  transition: background-color 0.2s ease;
}

.menu-item:hover {
  background-color: #f0f0f0;
  cursor: pointer;
}

#menu-toggle:checked + .menu-icon + .sidebar {
  left: 0;
}

/* Main content */
main {
  margin-left: 1rem;
  padding: 2rem;
}
