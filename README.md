# tarea_notas-primer-intento
%programa para clasificar estudianes segun la nota 
%primer intento if eslse
%luego intentare utilizando suich case123
notas=rand(500,1)*5;
N=4 ;   
ni=find(notas<=2.95);
REP=notas(ni,:) %devuelbe un vector con las notas menores a 2.95
reprobaron=length(REP)
na=find(notas>=2.95<4);   %aprobo  
v=notas(na,:);

ns=find(notas>N);     %SOBRESALIENTE 
d=notas(ns,:);

ne=find(notas>4.2);    %exelente
e=notas(ne,:);


if notas<2.95
    i=('reprobo')
disp(w)           %notas menores a 2.95
rep=length(w)' %numero de estudiantes que reprobaron
else 
    a=('aprobo')
    disp(v)
    aprobaron=length(v)'   %APROBO
    aprobarons=length(d)'  %SOBRESALIENTE
    aprobarone=length(e)'  %EXELENTE
    pasaron=(aprobaron+aprobarons+aprobarone) %CANTIDAD TOTAL DE ALUMNOS QUE PASARON PROGRAMACION CON SARA
end 
 
