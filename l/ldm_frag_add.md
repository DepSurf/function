# Function: <code>ldm_frag_add</code>

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
In block/partitions/ldm.c (ffffffff813d0e9b)
Location: block/partitions/ldm.c:1296
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff814162db)
Location: block/partitions/ldm.c:1244
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff8143180b)
Location: block/partitions/ldm.c:1244
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff8143e83a)
Location: block/partitions/ldm.c:1244
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff8146ab9a)
Location: block/partitions/ldm.c:1244
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff8149e787)
Location: block/partitions/ldm.c:1244
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff814b8b2e)
Location: block/partitions/ldm.c:1241
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff814e7839)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff81500c09)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1227
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff815601b0-ffffffff8156030f: ldm_frag_add (STB_LOCAL)
ffffffff81561fae-ffffffff8156208e: ldm_frag_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1227
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff8157bca0-ffffffff8157bdff: ldm_frag_add (STB_LOCAL)
ffffffff81bf2eab-ffffffff81bf2f8b: ldm_frag_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1227
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff81583780-ffffffff815838ef: ldm_frag_add (STB_LOCAL)
ffffffff81be4d7f-ffffffff81be4e55: ldm_frag_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1227
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff815e9150-ffffffff815e92d2: ldm_frag_add (STB_LOCAL)
ffffffff81cd91ca-ffffffff81cd92f6: ldm_frag_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:1218
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff81698a90-ffffffff81698c12: ldm_frag_add (STB_LOCAL)
ffffffff81e8ccd7-ffffffff81e8cd78: ldm_frag_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81757bd0)
Location: block/partitions/ldm.c:1218
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff81757bd0-ffffffff81757e26: ldm_frag_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81795150)
Location: block/partitions/ldm.c:1218
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff81795150-ffffffff817953a6: ldm_frag_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ldm_frag_add(const u8 *data, int size, struct list_head *frags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d8ab0)
Location: block/partitions/ldm.c:1218
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
**Symbols:**

```
ffffffff817d8ab0-ffffffff817d8d06: ldm_frag_add (STB_LOCAL)
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
In block/partitions/ldm.c (ffff800010602c54)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (c07ae214)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (c00000000079e318)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffe00043e268)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff814f91e9)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff814e96f9)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff814f5279)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
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
In block/partitions/ldm.c (ffffffff8150e2d9)
Location: block/partitions/ldm.c:1227
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_get_vblks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
