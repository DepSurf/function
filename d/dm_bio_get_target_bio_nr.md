# Function: <code>dm_bio_get_target_bio_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff816a7d01)
Location: include/linux/device-mapper.h:307
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff817081c0)
Location: include/linux/device-mapper.h:334
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff8173a092)
Location: include/linux/device-mapper.h:334
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff81753b72)
Location: include/linux/device-mapper.h:360
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff817c5cc2)
Location: include/linux/device-mapper.h:357
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81806610)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81806610-ffffffff8180661e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818327a0)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff818327a0-ffffffff818327ae: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81874fa0)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81874fa0-ffffffff81874fae: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a6db0)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff818a6db0-ffffffff818a6dbe: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81976c60)
Location: drivers/md/dm.c:127
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81976c60-ffffffff81976c6e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197b840)
Location: drivers/md/dm.c:127
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8197b840-ffffffff8197b84e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8195fa20)
Location: drivers/md/dm.c:132
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8195fa20-ffffffff8195fa2e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a07a20)
Location: drivers/md/dm.c:101
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81a07a20-ffffffff81a07a2e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b6fa10)
Location: drivers/md/dm.c:118
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81b6fa10-ffffffff81b6fa24: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0c030)
Location: drivers/md/dm.c:114
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81d0c030-ffffffff81d0c044: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d75170)
Location: drivers/md/dm.c:116
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81d75170-ffffffff81d75184: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2c280)
Location: drivers/md/dm.c:116
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81e2c280-ffffffff81e2c294: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afbfb8)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffff800010afbfb8-ffff800010afbfe0: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdc4b8)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
c0bdc4b8-c0bdc4d4: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000be9f80)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
c000000000be9f80-c000000000be9f90: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ed196)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffe0006ed196-ffffffe0006ed1ba: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184cc30)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8184cc30-ffffffff8184cc3e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81814250)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff81814250-ffffffff8181425e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189c260)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff8189c260-ffffffff8189c26e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int dm_bio_get_target_bio_nr(const struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b8420)
Location: drivers/md/dm.c:124
Inline: False
Direct callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
**Symbols:**

```
ffffffff818b8420-ffffffff818b842e: dm_bio_get_target_bio_nr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
