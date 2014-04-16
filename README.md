wp8.1JumpList-SemanticZoom
==========================

Implement jump list on wp 8.1.

As you know ,the new  wp8.1 not support LongListSelector yet,so i just use SemanticZoom for it.

LongListSelector is now SemanticZoom

Instead of using the LongListSelector we now have SemanticZoom. SemanticZoom is not a list but much more useful. There are two state of the SemanticZoom, ZoomedInView and ZoomedOutView. As the names imply you have two states in and out. Two make a control similar to the LongListSelector one can use a List in zoomed in and a GridView in zoomed out and with them simulate a LongListSelector. But the SemanticZoom control can be used for much more, example list of places and a map or when you have subsections make a fast navigate on zoomed out etc.

<SemanticZoom>
    <SemanticZoom.ZoomedInView>
        <ListView/>
    </SemanticZoom.ZoomedInView>
    <SemanticZoom.ZoomedOutView>
        <GridView/>
    </SemanticZoom.ZoomedOutView>
</SemanticZoom>
http://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.semanticzoom.aspx

Windows Phone app: zoomed-out and zoomed-in views of a semantic zoom control
 ![image](http://i.msdn.microsoft.com/dynimg/IC713280.png)
 
 Api:
 http://msdn.microsoft.com/en-us/library/windows/apps/hh465319.aspx
