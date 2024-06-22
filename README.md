\documentclass{article}
\usepackage{tikz}
\usepackage{fontawesome5}
\usepackage[margin=0.5in]{geometry}  % Adjust margin if needed

\begin{document}

% Define a command for the black background and emoji
\newcommand{\backgroundemoji}{
    \begin{tikzpicture}[remember picture, overlay]
        % Black background
        \fill[black] (current page.south west) rectangle (current page.north east);
        % Pirate skull emoji with red color, opacity, and fixed position
        \node[opacity=0.5, text=red, anchor=north west, xshift=-2cm, yshift=-1cm] at (current page.north west) {\faSkullCrossbones[scale=5]};
    \end{tikzpicture}
}

% Use the command to draw the background and emoji
\backgroundemoji

% Your content goes here
\section*{Introduction}
This is a sample document with a black background and a pirate skull emoji.
\end{document}


- 👋 Hi, I’m @geeparagoso
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
geeparagoso/geeparagoso is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
