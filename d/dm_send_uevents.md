# Function: <code>dm_send_uevents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8169fc90)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff8169fc90-ffffffff8169fdf7: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff817010a0)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff817010a0-ffffffff817011fb: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81732e00)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81732e00-ffffffff81732f5b: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff8174bbe0)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff8174bbe0-ffffffff8174bd44: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff817bdf60)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff817bdf60-ffffffff817be0c4: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff818064b7-ffffffff81806517: dm_send_uevents.cold.4 (STB_LOCAL)
ffffffff81806200-ffffffff8180630c: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:134
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81832647-ffffffff818326a7: dm_send_uevents.cold.4 (STB_LOCAL)
ffffffff81832390-ffffffff8183249c: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81874e47-ffffffff81874ea7: dm_send_uevents.cold (STB_LOCAL)
ffffffff81874b90-ffffffff81874ca9: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff818a6c57-ffffffff818a6cb7: dm_send_uevents.cold (STB_LOCAL)
ffffffff818a69a0-ffffffff818a6ab9: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81976af7-ffffffff81976b57: dm_send_uevents.cold (STB_LOCAL)
ffffffff819767f0-ffffffff81976909: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81c27f00-ffffffff81c27f60: dm_send_uevents.cold (STB_LOCAL)
ffffffff8197b500-ffffffff8197b619: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81c1a0c5-ffffffff81c1a125: dm_send_uevents.cold (STB_LOCAL)
ffffffff8195f730-ffffffff8195f849: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81d29c24-ffffffff81d29c84: dm_send_uevents.cold (STB_LOCAL)
ffffffff81a05070-ffffffff81a05189: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81ef5f8c-ffffffff81ef5fec: dm_send_uevents.cold (STB_LOCAL)
ffffffff81b6cdc0-ffffffff81b6cee2: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81d08ed0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81d08ed0-ffffffff81d09053: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81d72050)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81d72050-ffffffff81d721d3: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffff81e29120)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff81e29120-ffffffff81e292a3: dm_send_uevents (STB_GLOBAL)
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
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffff800010afbb60)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffff800010afbb60-ffff800010afbcd0: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (c0bdc074)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
c0bdc074-c0bdc210: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (c000000000be99a0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
c000000000be99a0-c000000000be9bc0: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-uevent.c (ffffffe0006ecd4e)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffe0006ecd4e-ffffffe0006ecec8: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff8184cad7-ffffffff8184cb37: dm_send_uevents.cold (STB_LOCAL)
ffffffff8184c820-ffffffff8184c939: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff818140f7-ffffffff81814157: dm_send_uevents.cold (STB_LOCAL)
ffffffff81813e40-ffffffff81813f59: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff8189c107-ffffffff8189c167: dm_send_uevents.cold (STB_LOCAL)
ffffffff8189be50-ffffffff8189bf69: dm_send_uevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dm_send_uevents(struct list_head *events, struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-uevent.c (0)
Location: drivers/md/dm-uevent.c:121
Inline: False
Direct callers:
  - drivers/md/dm.c:event_callback
```
**Symbols:**

```
ffffffff818b82c7-ffffffff818b8327: dm_send_uevents.cold (STB_LOCAL)
ffffffff818b8010-ffffffff818b8129: dm_send_uevents (STB_GLOBAL)
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
