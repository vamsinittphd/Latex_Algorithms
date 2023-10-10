# Latex_Algorithms  
This contains a code for writing LaTeX Algorithms  

#Code for LaTeX algorithm  
##Include the below code in the \usepackage codes  

Include these statements in the beginning  
\usepackage[margin=1.5in]{geometry}    % For margin alignment  
\usepackage[english]{babel}  
\usepackage[utf8]{inputenc}  
\usepackage{algorithm}  
\usepackage{arevmath}     % For math symbols  
\usepackage[noend]{algpseudocode}  

##Code for Latex code  

\begin{algorithm}  
\caption{Caption here}  
\begin{algorithmic}[1]  

\Procedure{Name}{\vphantom{ }}:         
\Comment{This is a test}  
    \State Input: Input parameters  
    \State Output: output parameters  
    \State \textbf{Step 1:}    
    \For{each epoch X}  
        \State \texttt{go to step-2}  
    \EndFor  
    \State \textbf{Step 2:} (Reading something)  
    \For{each $Condition$}  
        \For{each $Condition$}  
            \State for statements  
        \EndFor  
    \EndFor  
    \Step Step 3: (step name)  
    \For{each $Condition$}  
        \For{each $Condition$}  
            \If{$\pi_{i_{X}}\neq \mu_{i_{X-1}}$}  
            \State $P$= $P+1$  
            % \ElsIf{$Condition \neq 5$}  
            \Else  
                \State $P$= $P$  
            \EndIf  
        \EndFor  
    \EndFor  
    \Step Step 4: (Return)  
    \If{$Condition$}  
        \State Return the highest cccc value CH to the lowest cccc value as xx\\  \vphantom{}\qquad\quad tttttttt to ttttttttt (Step 5).  
    \EndIf  
    \State Step 5: Return the highest cccc value CH to the lowest cccc value as xx\\  \vphantom{}\qquad\quad tttttttt to ttttttttt (Step 5).  
\EndProcedure  

\end{algorithmic}  
\end{algorithm}  
 
