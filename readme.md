#TIC-TAC-TOE 3D

My first Three.js game!

Design inspired by: [Karim Maaloul's 'Aviator' Animation](http://tympanus.net/codrops/2016/04/26/the-aviator-animating-basic-3d-scene-threejs/)

---

Pseudocode:

<pre></code>
// I have cube id's which i can use to refer to via scene.children

// have a model that represents these ID's or name

// if an object is clicked
    // update the model into newModel

// { x:  }

// render(newModel)
    //for each
        // newModel[i].object.material.color = red;
        // newModel[i].object.material.color = red;

// model


{
    turn: 'o',
    cells: [null, null, 'o', null, null, null, null, null, null]
}

</code>
</pre>


Instead of "changes happen anywhere at anytime"
You can then say "all requested changes pass into and are verified and executed through this one workflow function"

So now a humble "click" doesn't change anything. It just tells update what it wants to change and update thinks about it and takes it from there.
