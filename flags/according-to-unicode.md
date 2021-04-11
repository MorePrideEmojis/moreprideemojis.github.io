---
title: Pride Flags, According To Unicode
image: /images/Flags/Large/prideflag_big_genderfluidemoji.png
description: Somewhat absurd emojified pride flags.
---

The "Pride Flags, According to Unicode" campaign takes a suggestion to "leverage existing Unicode symbols" to its logical, yet absurd, extreme.  Unicode believes that existing emojis are adequate to represent represent and simulate pride flags.  This is clearly not the case.

Many people use heart emojis to form various flags.  That sort of works for a few flags, but not all.  There are a limited number of heart emoji colors available, so the color schemes of many flags cannot be simulated.  For instance, the asexual flag is black, grey, white, and purple.  However, there's no grey heart emoji.  So what are we supposed to do?  Leaving out grey is not acceptable, because the grey is an integral part of the flag.  Do we substitute something grey in its place, like maybe an elephant or a wolf or the moon?  🖤🐘🤍💜, 🖤🐺🤍💜, and 🖤🌚🤍💜 are ridiculous.  And even when there are similar colors, they're usually not quite the right shade.  The deep magenta stripe of the bi flag will get usually get replaced by red, and there's no way to represent the different shades of the same color, as found on the lesbian or aro flags.  Finally, what about flags that aren't just stripes?  The intersex flag has an open purple ring on it.  That's not something that comes across in a series of colored hearts.

We shouldn't be forced to settle for these half-measures.  We need more pride emojis.

<h1>Campaign Pages</h1>

{%- assign campaign_paths = site.pages | map: "path" -%}
	
{%- for path in campaign_paths -%}
  {%- if  path contains "flags/" -%}
	{%- unless path contains "according-to-unicode" -%}
	  {%- assign my_page = site.pages | where: "path", path | first -%}
	  {%- if my_page.title -%}
	  <p>
        <a class="page-link" href="{{ my_page.url | relative_url }}">
	      <h3>{{ my_page.title | escape }}</h3>
	      <img src="{{ my_page.image }}" alt={{my_page.title | escape }}/>
		</a>
      <p>
	  <hr/>
      {%- endif -%}
    {%- endunless -%}
  {%- endif -%}
{%- endfor -%}