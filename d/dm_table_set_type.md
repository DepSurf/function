# Function: <code>dm_table_set_type</code>

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
In drivers/md/dm-table.c (ffffffff816a62a5)
Location: drivers/md/dm-table.c:821
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81704dc0)
Location: drivers/md/dm-table.c:842
Inline: False
```
**Symbols:**

```
ffffffff81704dc0-ffffffff81704dce: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81736c70)
Location: drivers/md/dm-table.c:836
Inline: False
```
**Symbols:**

```
ffffffff81736c70-ffffffff81736c7e: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8174fff0)
Location: drivers/md/dm-table.c:876
Inline: False
```
**Symbols:**

```
ffffffff8174fff0-ffffffff8174fffe: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c21d0)
Location: drivers/md/dm-table.c:878
Inline: False
```
**Symbols:**

```
ffffffff817c21d0-ffffffff817c21de: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180aae0)
Location: drivers/md/dm-table.c:879
Inline: False
```
**Symbols:**

```
ffffffff8180aae0-ffffffff8180aaee: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81836ad0)
Location: drivers/md/dm-table.c:877
Inline: False
```
**Symbols:**

```
ffffffff81836ad0-ffffffff81836ade: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818796e0)
Location: drivers/md/dm-table.c:877
Inline: False
```
**Symbols:**

```
ffffffff818796e0-ffffffff818796ee: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ab4e0)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffffffff818ab4e0-ffffffff818ab4ee: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197b6b0)
Location: drivers/md/dm-table.c:858
Inline: False
```
**Symbols:**

```
ffffffff8197b6b0-ffffffff8197b6be: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197fd90)
Location: drivers/md/dm-table.c:816
Inline: False
```
**Symbols:**

```
ffffffff8197fd90-ffffffff8197fd9e: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81963f10)
Location: drivers/md/dm-table.c:802
Inline: False
```
**Symbols:**

```
ffffffff81963f10-ffffffff81963f1e: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0bec0)
Location: drivers/md/dm-table.c:802
Inline: False
```
**Symbols:**

```
ffffffff81a0bec0-ffffffff81a0bece: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b743f0)
Location: drivers/md/dm-table.c:803
Inline: False
```
**Symbols:**

```
ffffffff81b743f0-ffffffff81b74406: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11280)
Location: drivers/md/dm-table.c:802
Inline: False
```
**Symbols:**

```
ffffffff81d11280-ffffffff81d11296: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7a710)
Location: drivers/md/dm-table.c:797
Inline: False
```
**Symbols:**

```
ffffffff81d7a710-ffffffff81d7a726: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e318b0)
Location: drivers/md/dm-table.c:818
Inline: False
```
**Symbols:**

```
ffffffff81e318b0-ffffffff81e318c6: dm_table_set_type (STB_GLOBAL)
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
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b01c00)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffff800010b01c00-ffff800010b01c2c: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be0dec)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
c0be0dec-c0be0e08: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf0ae0)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
c000000000bf0ae0-c000000000bf0af0: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f1644)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffffffe0006f1644-ffffffe0006f166e: dm_table_set_type (STB_GLOBAL)
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
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81851360)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffffffff81851360-ffffffff8185136e: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81818970)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffffffff81818970-ffffffff8181897e: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a0990)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffffffff818a0990-ffffffff818a099e: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table *t, enum dm_queue_mode type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bcbd0)
Location: drivers/md/dm-table.c:875
Inline: False
```
**Symbols:**

```
ffffffff818bcbd0-ffffffff818bcbde: dm_table_set_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int type</code> ➡️ <code>enum dm_queue_mode type</code>
</li>
</ul>
</details>
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
