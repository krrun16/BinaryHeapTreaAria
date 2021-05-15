# Binary_Heap_Tree_ARIA

Binary Heap Tree implementation with ARIA attribute

Link to project: https://ljflores.git-pages.research.uiowa.edu/binary_heap_tree_aria (currently doesn't work -- see the rest of README.md for details)

The user should hear "changed node" when they focus on a changed node.

# TODO

1. research-git.uiowa.edu gave Laura a lot of problems with deploying the website. If you visit Settings --> Pages, it says that the website is served, but clicking on the link does not work. I tried it with the non-UIowa affiliated version of GitLab, and the website worked just fine. Perhaps the ITS department will have suggestions about how to make Gitlab-Pages work with research-git.uiowa.edu.

2. Brandon suggests that we need to think about the tutorial for getting users accustomed to the layout. Users of course know how to navigate web elements like lists, headers, and links but we need to tell them that the tree is organized as “headers for nodes…lists for …etc). And that the steps are different web pages. Laura has implemented this under "Framework," but it might need to be revised with more concise wording.

3. We need to describe the Binary Heap algorithm somewhere on the webpage (part of tutorial).

4. Implement a "jump from first step to last step" functionality.

5. Proofread that links to parents/children are correct. (Laura has done this a lot already, but it might be good to have someone go through everything a few more times.)

6. Some of Kyle's comments still need to be addressed:
    
    Using NVDA:
    I noticed that my header comments (e.g., H, Shift+H, 1-4) were reading aloud the information, but not actually selecting the node. So when I
    pressed +/- it would go to the checkbox, which I had focused on last. It wasn’t until I pressed enter after hearing the node’s information that
    my cursor remained at the node when switching between steps. Perhaps it is worth mentioning that people have to press Enter to select a node? I
    am not sure there is a way to put focus on the node without pressing enter.
    
    Using JAWS:
    When I was focused on 60 (root) for example, and then pressed “3” to go to 10, it actually quickly read “30 Heading Level 2” first. In other
    words, JAWS wanted me to understand what the parent was. But when I clicked Shift 1, then it went straight back to root.
    I am reading at the character level in JAWS by default, so the interaction is quite different regarding reading aloud characters. Was VoiceOver
    at the character level or word level by default? We’ll need to specify to our participants what we are looking for.
    I did not have to press Enter to move nodes into focus. Is this also how it works for VoiceOver? So apparently my issue above is NVDA specific.

