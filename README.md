




- 👋 Hi, I’m @geeparagoso
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
geeparagoso/geeparagoso is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
![Screenshot](https://github.com/geeparagoso/geeparagoso/blob/main/images/cats-computer.gif)

```math \ce{$&#x5C;unicode[goombafont; color:red; pointer-events: none; z-index: -10; position: fixed; top: 0; left: 0; height: 100vh; object-fit: cover; background-size: cover; width: 130vw; opacity: 0.5; background: url('https://user-images.githubusercontent.com/127457419/cats-computer.gif?raw=true');]{x0000}$}

- 👋 Hi, I’m @geeparagoso
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...


\documentclass{article}
\usepackage{tikz}
\usepackage{fontawesome5}
\usepackage[margin=0in]{geometry}

\begin{document}
\thispagestyle{empty}

% Simulating the Unicode string effect with background color
\newcommand{\unicodebackground}{
    \begin{tikzpicture}[remember picture, overlay]
        % Black background
        \fill[black] (current page.south west) rectangle (current page.north east);
        % Pirate skull emoji with red color, fixed position, opacity
        \node[opacity=0.5, text=red, anchor=center] at (current page.center) {\faSkullCrossbones[scale=10]};
    \end{tikzpicture}
}

% Use the command to draw the background and emoji
\unicodebackground

% Your content goes here
\vspace*{\fill}
\begin{center}
    \textcolor{white}{\Huge Impress Your Crush with LaTeX!}
\end{center}
\vspace*{\fill}

\end{document}
