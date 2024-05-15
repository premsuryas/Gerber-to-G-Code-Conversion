# Gerber-to-G-Code-Conversion
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output






# G Code
### Engraving G Code:
!(![u1](https://github.com/premsuryas/Gerber-to-G-Code-Conversion/assets/147473858/7781d992-9643-41a5-a323-6535d1d42f03)
)






### Drill G Code:
!(![u2](https://github.com/premsuryas/Gerber-to-G-Code-Conversion/assets/147473858/e174a1a3-5d44-4617-9921-54ef5d65d581)
)






### Cutting G Code:
!(![u3](https://github.com/premsuryas/Gerber-to-G-Code-Conversion/assets/147473858/84d0e62d-52f1-4ef4-a5d6-29364dda9156)
)






# Result

Thus the Gerber File into G-Code using Copper CAM.
