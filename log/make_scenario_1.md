#

Create a base on Airtable called `Make or n8n` - https://airtable.com/

#

Use ChatGPT as your scriptwriter - https://chatgpt.com/c/68157044-e9bc-8002-97a0-2ab0885f687c

## Prompt 1

```txt
Write a short form video script highlighting insights from Mark Zuckerberg in the early scaling days of Facebook.com
```

## Prompt 2

```txt
Synthesize these insights into 4 short form video scripts

1. A 10 second script
2. A 20 second script
3. A 30 second script
4. A 60 second script
```

## Prompt 3

```txt - Script 1
Move fast, break things, and build something people truly care about.
```

```txt - Script 2
The biggest risk is not taking any risk.
Move fast and break things.
If you're not breaking things, you're not moving fast enough.
```

```txt - Script 3
In a small dorm room at Harvard, Mark Zuckerberg rented a server for just $85 a month, coding Facebook himself. His philosophy was simple: ‘Don’t build services just for money. Earn money to build better services.’
Driven by passion, Zuckerberg focused relentlessly, turning Facebook from a dorm-room idea into a worldwide platform.
```

```txt - Script 4
I literally coded Facebook from a dorm room, renting a server for $85 a month. It wasn’t glamorous. It was relentless, dedicated work.
The biggest risk was always not taking any risks.
Every day, I’d ask myself, ‘Am I doing the most important thing?’
We weren't building Facebook just for money; we earned money to build better things.
Great companies are driven by passion, vision, and courage—by people who move fast, break rules, and focus relentlessly on their mission.
```

## Prompt 4

```txt
Link to 10 creative commons photos of the early hyperscaling days of Facebook
```

#

Create a table in Airtable with 2 columns: `Record ID [Number]`, `Script`, `Photo`. Then add the script and photos.

#

Create the Make.com scenario

## Connect Airtable

- Airtable token or key
- Go to Airtable settings and go the the `Builder Hub`
- Create a `Personal access token` called `slideshow_generator` and the following "scopes"
  - `data.records:read`
  - `schema.bases:read`
- Select the base to allow access to ie: `Make or n8n`


## Built scenario (view `scenario_1_ref_photos`)

- https://json2video.com/docs/v2/api-reference/json-syntax/element/image
- https://json2video.com/docs/v2/api-reference/json-syntax/element/voice
- https://json2video.com/docs/v2/api-reference/json-syntax/movie
  - initially use `quality: low` & `resolution: sd`
  - then use `quality: high` & `resolution: full-hd`

## Generate landscape AND vertical video

- See `scenario_1_ref_photos/9.png`
- Duplicate last node
- use `full-hd` & `instagram-story`

##