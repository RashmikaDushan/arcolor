<h1 align="center">AR Coloring App</h1>

<h3 align="center">Welcome to the AR Coloring App! This app, developed with Unity and Vuforia, brings a cool experience to children by transforming their colored drawings into animated 3D models. Simply color the pictures in the book, scan them with the app, and watch the artwork come to life!</h3>

---

## Installation
　1. Clone a repository or download it as zip.
```
    git clone https://github.com/RashmikaDushan/arcolor.git
```
　2. Importing the AR Engine SDK to be used together. <br />
　　(You can use MaxstAR, EasyAR, Vuforia, ARFoundation(ARkit, ARcore)) <br />

<br />
 **Create Android App Project Demo(https://youtu.be/b5zSwDiwE4Q)**<br />
  **Create iOS App Project Demo(https://youtu.be/s1TcKE2PzXk)**<br /><br />

　**1. Create Project** <br />
 　-　Create an empty Unity3D project. <br /> <br />
  
　**2. Import Vuforia Unity Package** <br />
 　-　Importing the Vuforia Engine AR Unity Package(9.5.4v +). <br /> <br />

　**3. Import Sample Package** <br />
　-　After extracting the downloaded file, <br />
　　 import ColorMappingWithVuforiaSample.unitypackage from <br />
　　 ColorMapping-master -> Sample folder.<br /><br />
 
　**4. Import Native Library** <br />
 　-　Import ‘libAirarColorMap.so, libopencv_java3.so’ file for Android. <br />
 　 　(Set the CPU to ARM64 in the platform settings of the libAirarColorMap.so, libopencv_java3.so files.) <br />
 　-　Import ‘libAirarColorMap.a, opencv2.framework’ file for iOS. <br /> <br />
 
　**5. Player Settings for Android**
<table>
<tr><td>Allow 'unsafe' code</td><td>Check the Allow 'unsafe' code</td></tr>
<tr><td>Scripting Backend</td><td>Select IL2CPP</td></tr>
<tr><td>Target Architectures</td><td>Check Arm64 architecture(uncheck ARM7)</td></tr>
<tr><td>Scripting Define Symbols</td><td>Add 'USE_VUFORIA' into Scripting Define Symbols</td></tr>
</table>
<br />

　**6. Player Settings for iOS**
 <table>
<tr><td>Allow 'unsafe' code</td><td>Check the Allow 'unsafe' code</td></tr>
<tr><td>Scripting Backend</td><td>Select IL2CPP</td></tr>
<tr><td>Target Architectures</td><td>Check Arm64 architecture(uncheck ARM7)</td></tr>
<tr><td>Scripting Define Symbols</td><td>Add 'USE_VUFORIA' into Scripting Define Symbols</td></tr>
</table>
<br />

　**7. Setting for 3D Contents**
<table>
<tr> <td>‘coloring’ tag　　　　　</td><td>Set ‘coloring’ tag for Object containing the material <br/> to which the colored texture is applied</td></tr>
</table>
<br />

　**8. VuforiaColorMapping.cs** <br /><br />
<table>
<tr><td>ImageTaget　　　　　　</td><td>Vuforia ImageTargetBehaviour</td></tr>
<tr><td>ARContents</td><td>3D object to augment</td></tr>
<tr><td>RealWidth</td><td>Actual horizontal size of the marker image</td></tr>
<tr><td>RealHeight</td><td>Actual vertical size of the marker image</td></tr>
</table>
<br />
 
 　**9. Build** <br />
　-　Build by selecting the VuforiaSample scene under ColorMapping -> Scenes.<br /><br /><br />


### Prerequisites

- Unity 2020.3 or higher
- Vuforia Engine SDK

## Contact

For any questions or feedback, please contact us at:

- **Email**: [kbrashmikadushan@gmail.com](mailto:kbrashmikadushan@gmail.com)


Thank you for using the AR Coloring App! Enjoy bringing your drawings to life!




