# MusicXML

I love to make music and I love to program.
So how about we make music with programming languages?

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE score-partwise PUBLIC "-//Recordare//DTD MusicXML 3.1 Partwise//EN" "http://www.musicxml.org/dtds/partwise.dtd">
<score-partwise version="3.1">
  <part-list>
    <score-part id="P1">
      <part-name>Music</part-name>
    </score-part>
  </part-list>
  <part id="P1">
    <measure number="1">
      <note>
        <pitch>
          <step>E</step>
          <octave>5</octave>
        </pitch>
        <duration>4</duration>
        <type>quarter</type>
      </note>
      <!-- More notes go here... -->
    </measure>
  </part>
</score-partwise>

```

This example shows a simple XML file but it is used for MusicXML programs.