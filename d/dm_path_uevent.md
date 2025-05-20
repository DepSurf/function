# Function: <code>dm_path_uevent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8169fe00)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff8169fe00-ffffffff8169ffed: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81701200)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff81701200-ffffffff817013ed: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81732f60)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff81732f60-ffffffff8173314d: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8174bd50)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff8174bd50-ffffffff8174bf2b: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff817be0d0)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff817be0d0-ffffffff817be2ab: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff81806517-ffffffff818065c4: dm_path_uevent.cold.5 (STB_LOCAL)
ffffffff81806310-ffffffff8180645b: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8183273a)
Location: drivers/md/dm-uevent.c:183
Inline: True
```
**Symbols:**

```
ffffffff818326a7-ffffffff81832754: dm_path_uevent.cold.5 (STB_LOCAL)
ffffffff818324a0-ffffffff818325eb: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81874ea7)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffff81874ea7-ffffffff81874f55: dm_path_uevent.cold (STB_LOCAL)
ffffffff81874cb0-ffffffff81874df0: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff818a6cb7)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffff818a6cb7-ffffffff818a6d65: dm_path_uevent.cold (STB_LOCAL)
ffffffff818a6ac0-ffffffff818a6c00: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81976bf8-ffffffff81976c13: dm_path_uevent.cold (STB_LOCAL)
ffffffff81976a20-ffffffff81976a9a: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81c28001-ffffffff81c2801c: dm_path_uevent.cold (STB_LOCAL)
ffffffff8197b730-ffffffff8197b7aa: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81c1a125-ffffffff81c1a1d3: dm_path_uevent.cold (STB_LOCAL)
ffffffff8195f850-ffffffff8195f990: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81d29c84-ffffffff81d29d35: dm_path_uevent.cold (STB_LOCAL)
ffffffff81a05190-ffffffff81a05311: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81ef5fec-ffffffff81ef609d: dm_path_uevent.cold (STB_LOCAL)
ffffffff81b6cef0-ffffffff81b6d07e: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81d09070)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81d09070-ffffffff81d092fb: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81d721f0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81d721f0-ffffffff81d7247b: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81e292c0)
Location: drivers/md/dm-uevent.c:170
Inline: False
```
**Symbols:**

```
ffffffff81e292c0-ffffffff81e2954b: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffff800010afbcd0)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffff800010afbcd0-ffff800010afbee8: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (c0bdc210)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
c0bdc210-c0bdc3f8: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (c000000000be9bc0)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
c000000000be9bc0-c000000000be9e84: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffe0006ecec8)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffe0006ecec8-ffffffe0006ed0d0: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8184cb37)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffff8184cb37-ffffffff8184cbe5: dm_path_uevent.cold (STB_LOCAL)
ffffffff8184c940-ffffffff8184ca80: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81814157)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffff81814157-ffffffff81814205: dm_path_uevent.cold (STB_LOCAL)
ffffffff81813f60-ffffffff818140a0: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8189c167)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffff8189c167-ffffffff8189c215: dm_path_uevent.cold (STB_LOCAL)
ffffffff8189bf70-ffffffff8189c0b0: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_path_uevent(enum dm_uevent_type event_type, struct dm_target *ti, const char *path, unsigned int nr_valid_paths);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff818b8327)
Location: drivers/md/dm-uevent.c:170
Inline: True
```
**Symbols:**

```
ffffffff818b8327-ffffffff818b83d5: dm_path_uevent.cold (STB_LOCAL)
ffffffff818b8130-ffffffff818b8270: dm_path_uevent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
