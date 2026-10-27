---
layout: default
title: Telegrams on the road to Paris
permalink: /telegrams/
eyebrow: EAA129 · Centennial dispatch desk
description: Follow key milestones from the November 3 campaign launch through the May 20–21 crossing, with telegram-style dispatches and EAA129 event links.
---

{% assign event_url = site.chapter_event_url | strip %}

**Modern historical reconstruction · 1922–1927 story chapters.** These are newly written centennial messages, not archival telegrams or quotations. The dispatch desk tells the story from the ground: do not portray these as transmissions from Lindbergh’s airplane. Historical milestone wording remains subject to source-ledger approval.

{% if event_url != '' %}
<p><a class="button" href="{{ event_url | escape }}">Explore the story and EAA129 event →</a></p>
{% else %}
**Draft delivery status:** The EAA129 event-page URL is awaiting confirmation. SMS copy below is a draft; replace the link placeholder before scheduling messages.
{% endif %}

## The road to Paris · November 3, 2026–May 11, 2027

These twelve key-event dispatches accompany selected chapters in the [weekly release calendar]({{ '/releases/' | relative_url }}). **Publish dates are campaign dates; historical datelines identify the period being retold.** After the November 3 launch, the campaign revisits earlier milestones before returning to preparations for Paris. These are retrospective chapters, not anniversary-day reports. The flight series follows on May 20–21.

Use the full telegram as a social card or chapter-page feature and the matching short text for subscribers. Each draft links back to the EAA129 chapter event page.

{% for wire in site.data.leadup_telegrams %}
<section class="telegram" aria-labelledby="leadup-{{ wire.id }}">
<p class="telegram-label">EAA129 CENTENNIAL WIRE · ROAD TO PARIS {{ forloop.index }} · MODERN RECONSTRUCTION</p>
<h2 id="leadup-{{ wire.id }}">{{ wire.title | escape }}</h2>
<dl><dt>Publish</dt><dd>{{ wire.publish | escape }}</dd><dt>From</dt><dd>CENTENNIAL DESK · {{ wire.desk | escape }}</dd><dt>To</dt><dd>EAA129 AND FRIENDS OF AVIATION</dd><dt>Historical chapter</dt><dd>{{ wire.history | escape }}</dd></dl>
<p class="telegram-message">{{ wire.message | escape }}</p>
</section>

<p><strong>SMS draft · {{ wire.publish | escape }}</strong></p>
<blockquote><p>EAA129 | HISTORY RECREATED: {{ wire.sms | escape }} Story + event: {% if event_url != '' %}<a href="{{ event_url | escape }}">{{ event_url | escape }}</a>{% else %}[EAA129 EVENT PAGE URL]{% endif %}</p></blockquote>
{% endfor %}

## Follow the flight · May 20–21, 2027

Publish these on the centennial dates. The datelines inside the telegrams refer to the historical story. Use date-level scheduling until the history lead approves precise milestone times and their time zones. An ocean-gap dispatch is retrospective context, not a confirmed contemporary sighting.

<section class="telegram" aria-labelledby="wire-01">
<p class="telegram-label">EAA129 CENTENNIAL WIRE · 01 · MODERN RECONSTRUCTION</p>
<h2 id="wire-01">Departure watch</h2>
<dl><dt>From</dt><dd>ROOSEVELT FIELD · NEW YORK</dd><dt>To</dt><dd>ALL FOLLOWING THE STORY</dd><dt>Historical date</dt><dd>MAY 20 1927</dd></dl>
<p class="telegram-message">THE WAIT AT ROOSEVELT FIELD NEARS ITS END STOP SPIRIT OF ST LOUIS PREPARED FOR THE NEW YORK TO PARIS ATTEMPT STOP FOLLOW THE NEXT DISPATCH STOP</p>
</section>

**SMS draft · May 20, before the departure chapter**

> EAA129 | 1927 RECREATED: DEPARTURE WATCH STOP NEW YORK TO PARIS ATTEMPT APPROACHES STOP Story + event: {% if event_url != '' %}{{ event_url }}{% else %}[EAA129 EVENT PAGE URL]{% endif %}

<section class="telegram" aria-labelledby="wire-02">
<p class="telegram-label">EAA129 CENTENNIAL WIRE · 02 · MODERN RECONSTRUCTION</p>
<h2 id="wire-02">The Spirit is airborne</h2>
<dl><dt>From</dt><dd>ROOSEVELT FIELD · NEW YORK</dd><dt>To</dt><dd>THE CENTENNIAL DISPATCH DESK</dd><dt>Historical date</dt><dd>MAY 20 1927</dd></dl>
<p class="telegram-message">LINDBERGH DEPARTS ROOSEVELT FIELD STOP SPIRIT OF ST LOUIS SETS OUT FOR PARIS STOP ONE PILOT AND THE ATLANTIC AHEAD STOP</p>
</section>

**SMS draft · May 20, departure chapter**

> EAA129 | 1927 RECREATED: SPIRIT OF ST LOUIS AIRBORNE STOP PARIS AHEAD STOP Follow the flight + event: {% if event_url != '' %}{{ event_url }}{% else %}[EAA129 EVENT PAGE URL]{% endif %}

<section class="telegram" aria-labelledby="wire-03">
<p class="telegram-label">EAA129 CENTENNIAL WIRE · 03 · MODERN RECONSTRUCTION</p>
<h2 id="wire-03">Beyond the coast</h2>
<dl><dt>From</dt><dd>CENTENNIAL DISPATCH DESK · RETROSPECTIVE</dd><dt>To</dt><dd>THOSE WAITING ON SHORE</dd><dt>Historical date</dt><dd>MAY 20–21 1927</dd></dl>
<p class="telegram-message">THE CROSSING CONTINUES BEYOND NORTH AMERICA STOP NO POSITION REPORT FROM THE AIRPLANE IN THIS DISPATCH STOP ON SHORE THE WAIT CONTINUES STOP</p>
</section>

**SMS draft · May 20, ocean chapter**

> EAA129 | 1927 RECREATED: OVER THE ATLANTIC STOP THE WAIT ON SHORE CONTINUES STOP Explore the crossing + event: {% if event_url != '' %}{{ event_url }}{% else %}[EAA129 EVENT PAGE URL]{% endif %}

<section class="telegram" aria-labelledby="wire-04">
<p class="telegram-label">EAA129 CENTENNIAL WIRE · 04 · MODERN RECONSTRUCTION</p>
<h2 id="wire-04">Europe ahead</h2>
<dl><dt>From</dt><dd>CENTENNIAL DISPATCH DESK · EUROPE CHAPTER</dd><dt>To</dt><dd>ALL FOLLOWING THE CROSSING</dd><dt>Historical date</dt><dd>MAY 21 1927</dd></dl>
<p class="telegram-message">THE STORY REACHES THE EUROPEAN COAST STOP PARIS LIES AHEAD STOP FOLLOW THE FINAL STAGE OF THE NEW YORK TO PARIS ATTEMPT STOP</p>
</section>

**SMS draft · May 21, Europe chapter**

> EAA129 | 1927 RECREATED: EUROPE AHEAD STOP FOLLOW THE FINAL STAGE TO PARIS STOP Story + event: {% if event_url != '' %}{{ event_url }}{% else %}[EAA129 EVENT PAGE URL]{% endif %}

<section class="telegram" aria-labelledby="wire-05">
<p class="telegram-label">EAA129 CENTENNIAL WIRE · 05 · MODERN RECONSTRUCTION</p>
<h2 id="wire-05">Landed at Le Bourget</h2>
<dl><dt>From</dt><dd>PARIS · LE BOURGET CHAPTER</dd><dt>To</dt><dd>EAA129 AND FRIENDS OF AVIATION</dd><dt>Historical date</dt><dd>MAY 21 1927</dd></dl>
<p class="telegram-message">LINDBERGH LANDS AT LE BOURGET STOP FIRST SOLO NONSTOP NEW YORK TO PARIS FLIGHT COMPLETE STOP REMEMBER THE JOURNEY WITH EAA129 STOP</p>
</section>

**SMS draft · May 21, landing chapter**

> EAA129 | 1927 RECREATED: LANDED PARIS STOP FIRST SOLO NONSTOP NEW YORK TO PARIS FLIGHT COMPLETE STOP Story + EAA129 event: {% if event_url != '' %}{{ event_url }}{% else %}[EAA129 EVENT PAGE URL]{% endif %}

## From the wire to the chapter event

Each SMS leads to the **EAA129 chapter event page**, where readers should find the matching historical chapter and source notes alongside confirmed event date, location, attendance details, and registration information. Keep that destination consistent across SMS, social captions, and audio descriptions. Historical datelines above are not the local event schedule.

## Dispatch desk · publishing notes

- Use a paper telegram card for the full dispatch and plain text for SMS. Keep the reconstruction label visible in shared artwork and in every standalone message.
- Publish the twelve lead-up dispatches on their campaign dates, then the five flight dispatches in sequence. For SMS, offer the milestone series and the more frequent flight-week series as clear subscriber choices; a lighter flight-week option is departure and landing only.
- The schedule above is an editorial draft. Select a texting provider, confirm an opted-in audience and sender identity, and approve the final copy and send times before delivery. This static site does not send texts or collect phone numbers.
- Keep each SMS to one link. Check the complete message length with the actual URL and the provider’s required opt-out footer; these drafts may span multiple SMS segments.
- Set `chapter_event_url` in `_config.yml` to the confirmed public event page. Until then, link placeholders remain visibly marked as drafts.
- Maintain a source ledger for each milestone. Do not reuse unverified sample sighting times, invented eyewitness reports, corporate congratulations, or historical wire-service branding as evidence.
