<h1>
"scripts": {
"dev": "vite", => this will start server from main root / to accsess subfolder index.html go to 'http://localhost:5173/subfolder/'
"dev2": "vite subfolder", => vite server will start from (subfolder) and considere it as root folder and can't import any files outside subfolder
"build": "vite build",
"preview": "vite preview"
},
</h1>
