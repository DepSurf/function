# Function: <code>ext4_match</code>

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
In fs/ext4/namei.c (ffffffff812a3c25)
Location: fs/ext4/namei.c:1234
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_find_dest_de
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
In fs/ext4/namei.c (ffffffff812d3d0d)
Location: fs/ext4/namei.c:1243
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff812e9a4d)
Location: fs/ext4/namei.c:1245
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff81319236)
Location: fs/ext4/namei.c:1257
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
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
In fs/ext4/namei.c (ffffffff8133d976)
Location: fs/ext4/namei.c:1258
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136bf4e)
Location: fs/ext4/namei.c:1259
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8138442e)
Location: fs/ext4/namei.c:1260
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813adc00)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c6b40)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81413152)
Location: fs/ext4/namei.c:1346
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142673b)
Location: fs/ext4/namei.c:1335
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142d22e)
Location: fs/ext4/namei.c:1415
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff81429930-ffffffff81429a59: ext4_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff8148113e)
Location: fs/ext4/namei.c:1416
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff8147d730-ffffffff8147d859: ext4_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_match(struct inode *parent, const struct ext4_filename *fname, struct ext4_dir_entry_2 *de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814fff10)
Location: fs/ext4/namei.c:1462
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff814fff10-ffffffff81500071: ext4_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ext4_match(struct inode *parent, const struct ext4_filename *fname, struct ext4_dir_entry_2 *de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159a700)
Location: fs/ext4/namei.c:1467
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff8159a700-ffffffff8159a861: ext4_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ext4_match(struct inode *parent, const struct ext4_filename *fname, struct ext4_dir_entry_2 *de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d0fa0)
Location: fs/ext4/namei.c:1483
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff815d0fa0-ffffffff815d1101: ext4_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ext4_match(struct inode *parent, const struct ext4_filename *fname, struct ext4_dir_entry_2 *de);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81609760)
Location: fs/ext4/namei.c:1487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff81609760-ffffffff816098a7: ext4_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049e668)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c06604d0)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005ca184)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000321070)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bf120)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813afbb0)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bc706)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d16b0)
Location: fs/ext4/namei.c:1342
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
