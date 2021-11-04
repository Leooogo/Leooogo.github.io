---
layout: post
title: CSS Components
---

What are the two fundamental layout components?
Containers and Wrappers

What flex-item CSS property sets its 3 behaviors?
It's flex: flex-grow flex-shrink flex-basis;

✨✨✨✨✨
  The flex-grow CSS property sets the flex grow factor of a flex item's main size.
  
  The flex-shrink CSS property sets the flex shrink factor of a flex item. If the size of all flex items is larger than the flex container, items shrink to fit according to flex-shrink.
  
  The flex-basis CSS property sets the initial main size of a flex item. It sets the size of the content box unless otherwise set with box-sizing.
✨✨✨✨✨
  
What flexbox CSS property sets the relative position of flex-items horizontally inside the flexbox?
justify-content(default value: flex-start)

✨✨✨✨✨
  /* Positional alignment */
  justify-content: center;     /* Pack items around the center */
  justify-content: start;      /* Pack items from the start */
  justify-content: end;        /* Pack items from the end */
  justify-content: flex-start; /* Pack flex items from the start */
  justify-content: flex-end;   /* Pack flex items from the end */
  justify-content: left;       /* Pack items from the left */
  justify-content: right;      /* Pack items from the right */

  /* Baseline alignment */
  /* justify-content does not take baseline values */

  /* Normal alignment */
  justify-content: normal;

  /* Distributed alignment */
  justify-content: space-between; /* Distribute items evenly
                                     The first item is flush with the start,
                                     the last is flush with the end */
  justify-content: space-around;  /* Distribute items evenly
                                     Items have a half-size space
                                     on either end */
  justify-content: space-evenly;  /* Distribute items evenly
                                     Items have equal space around them */
  justify-content: stretch;       /* Distribute items evenly
                                     Stretch 'auto'-sized items to fit
                                     the container */

  /* Overflow alignment */
  justify-content: safe center;
  justify-content: unsafe center;

  /* Global values */
  justify-content: inherit;
  justify-content: initial;
  justify-content: revert;
  justify-content: unset;
✨✨✨✨✨

What flex-item CSS property sets its default size before remaining space is distributed?
It's flex-basis(default value: auto).
It can be a length (100px, 20%, etc) or a keyword. auto means "look at my width property", content means "size it based on my content".

What flexbox CSS property enables flex-items to be displayed in several lines rather than trying to fit all in one line?
It's flex-wrap: wrap; (default value: no-wrap)

✨✨✨✨✨
  flex-wrap: nowrap; /* Default value */
  flex-wrap: wrap;
  flex-wrap: wrap-reverse;

  /* Global values */
  flex-wrap: inherit;
  flex-wrap: initial;
  flex-wrap: revert;
  flex-wrap: unset;
✨✨✨✨✨

CSS components are for example a card, a button, etc. We use them like Lego bricks to build user interfaces.

What flexbox CSS property sets flex-items' vertical alignment inside the flexbox?
It's align-items (default value: flex-start)

✨✨✨✨✨
  /* Basic keywords */
  align-items: normal;
  align-items: stretch;

  /* Positional alignment */
  /* align-items does not take left and right values */
  align-items: center; /* Pack items around the center */
  align-items: start; /* Pack items from the start */
  align-items: end; /* Pack items from the end */
  align-items: flex-start; /* Pack flex items from the start */
  align-items: flex-end; /* Pack flex items from the end */

  /* Baseline alignment */
  align-items: baseline;
  align-items: first baseline;
  align-items: last baseline; /* Overflow alignment (for positional alignment only) */
  align-items: safe center;
  align-items: unsafe center;

  /* Global values */
  align-items: inherit;
  align-items: initial;
  align-items: revert;
  align-items: unset;
✨✨✨✨✨

What flexbox CSS property is neede to display flex-items above one another (and not side by side)?
It's flex-direction: column; (default value: row)
Other possible values row-reverse, column-reverse.

✨✨✨✨✨
  /* The direction text is laid out in a line */
  flex-direction: row;

  /* Like <row>, but reversed */
  flex-direction: row-reverse;

  /* The direction in which lines of text are stacked */
  flex-direction: column;

  /* Like <column>, but reversed */
  flex-direction: column-reverse;

  /* Global values */
  flex-direction: inherit;
  flex-direction: initial;
  flex-direction: revert;
  flex-direction: unset;
✨✨✨✨✨
