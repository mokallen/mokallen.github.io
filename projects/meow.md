---
layout: project
type: project
image: img/meow.jpg
title: "Meow"
date: 2023-01-13
published: true
labels:
  - Cats
  - Entertainment
  - AI
summary: "Meow is an AI cat generator."
---

Meow is an AI generator which allows users to generate cat images.

For this project, I was the lead programmer who was responsible for programming the various capabilities of the AI generator.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
