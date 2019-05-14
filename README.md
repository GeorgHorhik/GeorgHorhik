GeorgHorhik
#command for linux#
    sudo mount -oremount,rw /media/horhik/Work





program PZ2_1;

  begin
  
  var a,b:integer;
  
  WriteLn('Input a and b');
  
  readLn(a , b);
  
  writeLn( '(' +a+'+'+b+')'+'^2 ' + '=' +a+'^2' '+'+ '2'+'*'+a+'*'+''+b+'+'+b+'^2'+'=' + ((a+b)*(a+b)) );
  
  writeLn( '(' +a+'-'+b+')'+'^2 ' + '=' +a+'^2' '-'+ '2'+'*'+a+'*'+''+b+'+'+b+'^2'+'=' + ((a-b)*(a-b)) );
  
  writeLn( '(' +a+'-'+b+')'+'*'+ '(' +a+'+'+b+')' + '=' +a+'^2' + '-' +b+'^2'+'=' + ((a-b)*(a-b)) );
  
  end.




58cb1704c1c1dfcfc3147ebee4a58cb5ea185f82


dcc50a2e02f02b7fd1d6c3089abf920bc1744898
