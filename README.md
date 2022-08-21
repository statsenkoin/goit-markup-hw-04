# goit-markup-hw-03

    Не проходить валідацію рядок clip-path: inset(100%);

    .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    border: 0;
    padding: 0;

    white-space: nowrap;
    clip-path: inset(100%); //Властивість “clip-path” не існує
    clip: rect(0 0 0 0);    //The property “clip” is deprecated
    overflow: hidden;
    }
