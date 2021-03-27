1.void main() {
 // Specifying the length creates a fixed-length list.
  var list = new List(3);
  list[0] = 'a';
  list[1] = 'b';
  list[2] = 'c';
  print(list);
}

2.void main() {

// Leaving out the lenght creates a growable list.
  var growable = new List ();
  growable.addAll(['grow', 'able']);
  print(growable);
}

3.void main() {
//
  var list2 = ['also', 'growable','42'];
  print(list2);
}

4.void main() {
var list3 = [47, 3, 25];
  try {
    for (var item in list3) {
      if (item < 10) {
        list3.remove(item);
      }
    }
  } catch(e) {
    print('error');
  }
}