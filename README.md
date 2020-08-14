# melotronome
drum training metronome - random melody generator

My first android app idea;
DRUM PRACTISE TOOL

Every musician should know the benefit of practising to a metronome, especially drummers - but the process can be monotonous.
By creating a random repeating series of notes at variable tempos and time signatures, the melotronome takes drum practise to a whole new level, engaging the musical part of the brain as well as focusing on timing. 

GUI created with kivy, using a .kv file.

Pygames midi engine generates the audio. 


GUI is currently basic, utilising buttons to change time signature, and a slider to change tempo.

I will create an attractive GUI once I am happy with the functionality of the app.


The program is functional but once sound generation has started, tempo and time signature can't be edited until sound has been stopped, reducing fluidity of usage. 

Program currently allows for root note (first note in sequence) to be changed, but may remove this as for now serves no purpose.

May add indicator for note one of sequence, such as a visual cue, or a more defined note/chord.

Will eventually add more time signature options (more buttons!).

Need to find more efficient way of setting tempo, (text input instead of slider?)



I am still learning the prefered format of python in terms of spacing and comments, but have attempted to make the code as readable as possible.

Once the app has successfully run on an Android device, I will acquire feedback from target audience (drummers) to increase its functionality as a practise tool.
