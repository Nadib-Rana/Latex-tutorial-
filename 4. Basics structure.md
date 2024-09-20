**Creating a New Document**

1. **Log in or sign up:** Visit Overleaf's website and log in to your account or create a new one.
2. **Create a new project:** Click the "New Project" button and choose a template or start from scratch.
3. **Choose a document class:** Select the appropriate document class (e.g., article, book, report) based on your needs.
4. **Start writing:** Begin typing your content directly in the Overleaf editor.

**Basic LaTeX Structure**

* **Document class:** Defines the overall layout and style of your document.
* **Sections and subsections:** Organize your content using headings.
* **Text formatting:** Use commands like `\textbf`, `\textit`, and `\emph` for bold, italic, and emphasized text.
* **Lists:** Create numbered or unnumbered lists using `\begin{enumerate}` and `\begin{itemize}`, respectively.
* **Tables:** Use the `tabular` environment to create tables.
* **Figures and images:** Include images using the `graphicx` package and the `\includegraphics` command.

**Example:**

```latex
\documentclass{article} % Specifies the document class (article, book, report, etc.)

\begin{document}

\title{My First LaTeX Document} % Sets the title of the document
\author{Your Name} % Sets the author's name
\date{\today} % Inserts the current date

\maketitle % Creates the title page

This is a paragraph of text. % A simple paragraph

\section{A Section} % Creates a section heading

This is a section heading.

\subsection{A Subsection} % Creates a subsection heading

This is a subsection heading.

\begin{itemize}
\item Item 1 % Creates an unordered list
\item Item 2
\item Item 3
\end{itemize}

\end{document}
```

**Compiling Your Document**

* Overleaf automatically compiles your document as you type, showing you the rendered output in real time.
* You can also manually compile by clicking the "Compile" button or using the keyboard shortcut (usually Ctrl+Shift+K).



