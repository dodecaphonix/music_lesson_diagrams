# Open position triad voice leading cycles

(limited to the high four strings)

---

## Voicing definitions

First, let's define out voicings using C as our root.

Low root position `<R`

```
| - - 3 3 - - - - - - - - - - - - - - - - - - - -
5 - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - 1 - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
```

High root position `R>`

```
| - - 3 3 - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - 5 - - - - - - - - - - - - - - - - - - -
| - - 1 - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
```

Low first inversion `<1`

```
| - - - - - - 5 - - - - - - - - - - - - - - - - -
| - - - - 1 - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - 3 3 - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
```

High first inversion `1>`

```
| - - - - - - 5 - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - 1 - - - - - - - - - - - - - -
| - - - - - 3 3 - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
```

Low second inversion `<2`

```
| - - - - - - - - - - - 1 - - - - - - - - - - - -
| - - - - - - - 3 3 - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - 5 - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
```

High second inversion `2>`

```
| - - - - - - - - - - - 1 - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - 3 3 - - - - - - - - - -
| - - - - - - - - - 5 - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
```

---

## Voicing spans and centers

Next, if we look at the highest and lowest frets for each voicing, we can find each voicing's approximate center.

| voicing | low fret | high fret | center    |
|---------|----------|-----------|-----------|
| `<R`    | 0        | 4         | 2         |
| `R>`    | 3        | 5         | 4         |
| `<1`    | 5        | 7         | 6         |
| `1>`    | 6        | 10        | 8         |
| `<2`    | 8        | 12        | 10        |
| `2>`    | 10       | 14        | 12        |

The centers are every 2 frets.
The 6 voicings evenly divide the 12 half steps per octave.
Cool!

## Laying the centers back onto the fingerboard

Now let's place the notation for each voicing on top of its center.
We will repeat at the octave.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
   <R   R> <1   1> <2   2> <R   R> <1   1> <2
```

Let's leave off the `<` and `>` just to make it a bit easier to look at.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
    R   R   1   1   2   2   R   R   1   1   2
```

---

## Inspecting voice leading cycles

Here is where we get to the interesting part.
So far, we've only super imposed voicings with root C onto our diagrams.
Let's put a repeating pattern of roots onto the same diagram.
We will start with 4ths because they are extremely useful for things like ii V I progressions.
Here are C F B♭ E♭ all on the same diagram.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
    R   R   1   1   2   2   R   R   1   1   2
  1   2   2   R   R   1   1   2   2   R   R
    R   1   1   2   2   R   R   1   1   2   2
  2   2   R   R   1   1   2   2   R   R   1
```

### Ascending the neck

Let's say, with each chord change, we want to gradually ascend the neck.
With each new row, we will pick the voicing directly to the right.
One example would look like this.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
                                R>
                                  2>
                                    1>
                                      R>
```

So that is:
- C voiced `R>`
- F voiced `2>`
- B♭ voiced `1>`
- E♭ voiced `R>`

Since both C and E♭ are voiced `R>`, we can see that the cycle repeats!
If we go through every possibility of 4ths gradually ascending the neck, we can see that there only ends up being two of these cycles.

||: `R>` | `2>` | `1>` :||

||: `<R` | `<2` | `<1` :||

### Descending the neck

Now let's say, with each chord change, we want to gradually descend the neck.
With each new row, we will pick the voicing directly to the left.
One example would look like this.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
                                R>
                             <2
                            R>
                         <2
```

So that is:
- C voiced `R>`
- F voiced `<2`
- B♭ voiced `R>`
- E♭ voiced `<2`

If we go through every possibility of 4ths gradually descending the neck, we can see that there ends up being three cycles this time.

||: `R>` | `<2` :||

||: `1>` | `<R` :||

||: `2>` | `<1` :||

### An alternate way to descend the neck

What if, rather than picking the voicing directly to the left with each chord change, we go down two and then up one repeating?
The ascending patterns have easier fingerings in general.
The slightly larger jump when we descend simplifies the fingering of the next chord change by letting us ascend to it.
One example would look like this.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
                                R>
                          1>
                            R>
                      1>
```

So that is:
- C voiced `R>`
- F voiced `1>`
- B♭ voiced `R>`
- E♭ voiced `1>`

If we go through every possibility of 4ths going down two up one repeating we get the following.
There are lots of possibilities this time!

||: `R>` | `1>` :||

||: `<R` | `<1` :||

||: `1>` | `2>` :||

||: `<1` | `<2` :||

||: `2>` | `R>` :||

||: `<2` | `<R` :||

These patterns don't yield any new sounds that arn't available with the standard descending patterns.
They are purely for alternate fingerings.

---

## More complex voice leading cycles

This trick doesn't just work with 4ths.
We can generalize any repeating pattern in the same fashion.
Let's take the first three measures of John Coltrane's Giant Steps: B D G B♭ E♭.
These chords go up a minor 3rd and then up a 4th repeating.
Here are B D G B♭ E♭ all on the same diagram.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
      R   1   1   2   2   R   R   1   1   2
    2   R   R   1   1   2   2   R   R   1   1
      1   2   2   R   R   1   1   2   2   R
    R   1   1   2   2   R   R   1   1   2   2
      2   R   R   1   1   2   2   R   R   1
```

Let's gradually ascend the neck.
One example would look like this.

```
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
| - - - - - - - - - - - - - - - - - - - - - - - -
      ˚   ˚   ˚   ˚     :     ˚   ˚   ˚   ˚     :
                              R>
                               <R
                                 <2
                                    1>
                                      R>
```

That one ascending pattern ends up being this.

||: `R>` | `<R` | `<2` | `1>` :||

That is just one of a total of six possible for ascending that cycle.

---

## Summary

There are a lot of fun patterns to find here, and a lot to practice! :)
