# Brick-Instruction-Deconstructor
WORK IN PROGRESS!!!

> 📄 **License:** This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).  
> You may share and adapt the code and models, but **commercial use is prohibited.**

This app uses machine learning models trained on publicly available LEGO® instruction imagery to help users quickly identify which parts correspond to which steps in complex instruction booklets.

The goal is not to replace official LEGO® content, but to support fans, builders, and educators by reducing the time and visual strain involved in traditional instruction navigation.

This project is not affiliated with, endorsed by, or associated with The LEGO Group. All trademarks, including LEGO® and the LEGO® logo, are the property of The LEGO Group.

Test predictions page is <a href='https://autoupdatingbsod.github.io/Brick-Instruction-Deconstructor/'>here</a>

Page and Section model pipelines are <a href='https://github.com/AutoUpdatingBSoD/Brick-Instruction-Deconstructor/releases/tag/Testing)'>here</a>.

Python dependencies needed for the section model pipeline:

```pip install tensorflow ultralytics torch```

Though torch is technically optional, all I really use it for is GPU Acceleration in Training. It would survive without it provided you really wanted to edit that part out.



A YoloV5 or YoloV8 untrained but properly labelled dataset from Roboflow is also needed

XML Format for Output is <a href='https://www.bricklink.com/help.asp?helpID=207'> here</a>.

Stretch Goal CSV For Later (for personal reference) is <a href='https://rebrickable.com/downloads/'>here</a>.
