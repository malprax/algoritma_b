void main() {

  var pos = new Position(4);

  try {
    pos.x = 100;// runtime error
    print('${pos.x}');
  }  catch(e) {
    print('error');
  }
}

class Position {
   int x;
   int y;
  Position(this.x) : y = 0;
}