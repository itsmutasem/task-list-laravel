<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task Management System</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #0366d6;
            margin-top: 24px;
            margin-bottom: 16px;
        }
        h1 {
            font-size: 2em;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
        }
        h2 {
            font-size: 1.5em;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
        }
        code {
            background-color: rgba(27, 31, 35, 0.05);
            border-radius: 3px;
            padding: 0.2em 0.4em;
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
        }
        pre {
            background-color: #f6f8fa;
            border-radius: 3px;
            padding: 16px;
            overflow: auto;
        }
        .badge {
            display: inline-block;
            padding: 3px 6px;
            font-size: 14px;
            font-weight: 600;
            line-height: 1;
            color: #fff;
            background-color: #0366d6;
            border-radius: 2em;
            margin-right: 5px;
        }
        ul, ol {
            padding-left: 2em;
        }
        a {
            color: #0366d6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        img {
            max-width: 100%;
            box-sizing: content-box;
            background-color: #fff;
        }
    </style>
</head>
<body>
    <h1>Task Management System</h1>

    <p>
        <span class="badge" style="background-color: #FF2D20;">Laravel</span>
        <span class="badge" style="background-color: #38B2AC;">TailwindCSS</span>
        <span class="badge" style="background-color: #8BC0D0;">AlpineJS</span>
    </p>

    <p>A simple yet powerful Task Management System built with Laravel, Tailwind CSS, and Alpine.js.</p>

    <h2>Features</h2>
    <ul>
        <li>✅ Create, Read, Update, and Delete (CRUD) tasks</li>
        <li>✅ Mark tasks as complete/incomplete</li>
        <li>✅ Responsive design</li>
        <li>✅ Form validation</li>
        <li>✅ Success notifications</li>
        <li>✅ Paginated task listing</li>
        <li>✅ Clean, modern UI</li>
    </ul>

    <h2>Installation</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/yourusername/task-management-system.git
cd task-management-system</code></pre>
        </li>
        <li>Install dependencies:
            <pre><code>composer install
npm install</code></pre>
        </li>
        <li>Create and configure <code>.env</code> file:
            <pre><code>cp .env.example .env</code></pre>
        </li>
        <li>Generate application key:
            <pre><code>php artisan key:generate</code></pre>
        </li>
        <li>Run migrations:
            <pre><code>php artisan migrate</code></pre>
        </li>
        <li>Start the development server:
            <pre><code>php artisan serve</code></pre>
        </li>
    </ol>

    <h2>Usage</h2>
    <ol>
        <li>Access the application at <code>http://localhost:8000</code></li>
        <li>Use the navigation to:
            <ul>
                <li>View all tasks</li>
                <li>Create new tasks</li>
                <li>Edit existing tasks</li>
                <li>Mark tasks as complete/incomplete</li>
                <li>Delete tasks</li>
            </ul>
        </li>
    </ol>

    <h2>Technologies Used</h2>
    <h3>Backend:</h3>
    <ul>
        <li>Laravel 11</li>
        <li>PHP 8.2+</li>
    </ul>

    <h3>Frontend:</h3>
    <ul>
        <li>Blade templates</li>
        <li>Tailwind CSS</li>
        <li>Alpine.js</li>
    </ul>

    <h3>Database:</h3>
    <ul>
        <li>SQLite</li>
    </ul>

    <h2>File Structure</h2>
    <pre><code>task-management-system/
├── app/
│   ├── Models/
│   │   └── Task.php
│   └── Http/
│       └── Requests/
│           └── TaskRequest.php
├── resources/
│   └── views/
│       ├── layouts/
│       │   └── app.blade.php
│       ├── create.blade.php
│       ├── edit.blade.php
│       ├── form.blade.php
│       ├── index.blade.php
│       └── show.blade.php
├── routes/
│   └── web.php
└── database/
    ├── migrations/
    └── seeders/</code></pre>

    <h2>Contributing</h2>
    <p>Contributions are welcome! Please follow these steps:</p>
    <ol>
        <li>Fork the project</li>
        <li>Create your feature branch (<code>git checkout -b feature/AmazingFeature</code>)</li>
        <li>Commit your changes (<code>git commit -m 'Add some AmazingFeature'</code>)</li>
        <li>Push to the branch (<code>git push origin feature/AmazingFeature</code>)</li>
        <li>Open a Pull Request</li>
    </ol>
</body>
</html>
