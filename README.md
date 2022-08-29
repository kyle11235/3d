
- blender

        1. shaping model
        
                - view
                rotate = 2 fingers
                move = shift + 2 fingers
                zoom = control + 2 fingers
                trigger views from 3 directions = control + option + q
                trigger xray view = option + z

                - add cube
                Shift + A, Mesh, Cube
                
                - shape it
                edit mode, Proportional Editing (shift + O), transformations, and extrusions ...
                add new cube, join to main cube, then it mirrors

                - mirror
                edit mode, subdivide, delete right part of cube
                modifier property tab, add, mirror modifier, select clipping
                
                - smooth
                add a Subdivision Surface modifier
                object mode, right-click, then select “Shade Smooth”

        2. texturing

        3. rigging bones

                https://www.youtube.com/watch?v=XKCUpiClJK8
                
                - display/selectable
                add armature/bone, object data properties, viewport display, check 'in front'
                
                - extrude
                select armature, change to edit mode, extrude (create new bones from the selected)
                
                - bind bone to model
                select model & bone, commmand + p, with automatic weight

                - pose
                select bone, pose mode, change pose

                
        4. animation

                click animation workspace, object mode, click i to insert keyframe
                go to frame 100, move/rotate/scale, click i, play it

                - 2d vs 3d
                2D (‘frame by frame’) is very time consuming and methodical, but I would say you progress at a ‘steady pace’. The level of difficulty too will depend on your drawing skills- if you can draw quickly and ‘efficiently’ (getting the form right immediately) you will find it easier.

                3D is quicker in the sense that you don’t have to animate ‘every’ frame, as you set the beginning and ending position of your animated components, and the software will do the frames in-between (‘tweening’). In this way, you can animate in 3D far quicker than 2D.

                However, 3D is very technical and you have lots of other elements to consider outside of just animating: modeling, rigging, lighting, rendering, cameras, etc. And all of these things can break or run into issues…

                draw 2d > 3d = more dynamic
                3d > draw 2d = looks rigid

- unity3d

        - animation clip
        
                - ruby-adventure / 2d
                4 clips (4 pictures / clip), run into 4 directions

                - john-jaunt / 3d
                from imported/external FBX, bones inside character, john@idle, john@walk

        - animation controller / state machine
        
                - ruby-adventure
                X & Y params, 4 combinations as 4 states

                - john-jaunt
                1 param IsWalking, 2 states

        - reuse / custom

                - Animation from external sources
                https://docs.unity3d.com/Manual/AnimationsImport.html
        
                - Starter Assets - Third Person Character Controller
                https://www.youtube.com/watch?v=wZrCIxCZA6A


- 3d dancer

        - Easy Dancing Character Animation || Blender 2.93
        
                https://www.youtube.com/watch?v=NHQtU2v3zBU

        - Music Conditioned 3D Dance Generation with AIST++
        
                https://ai.googleblog.com/2021/09/music-conditioned-3d-dance-generation.html



        










