# Function: <code>adjust_for_msb_right_quirk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff815150b0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff815150b0-ffffffff81515151: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff81535af0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff81535af0-ffffffff81535b91: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff8159a1a0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff8159a1a0-ffffffff8159a246: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff815b5bb0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff815b5bb0-ffffffff815b5c56: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff815c09e0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff815c09e0-ffffffff815c0a88: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/packing.c (0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff81628760-ffffffff81628870: adjust_for_msb_right_quirk (STB_LOCAL)
ffffffff81cdb192-ffffffff81cdb2db: adjust_for_msb_right_quirk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/packing.c (0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff816f94a0-ffffffff816f95f3: adjust_for_msb_right_quirk (STB_LOCAL)
ffffffff81e939de-ffffffff81e93b04: adjust_for_msb_right_quirk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/packing.c (0)
Location: lib/packing.c:33
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff817ebde0-ffffffff817ebec3: adjust_for_msb_right_quirk (STB_LOCAL)
ffffffff82078aa8-ffffffff82078b59: adjust_for_msb_right_quirk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/packing.c (0)
Location: lib/packing.c:33
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff8182bf60-ffffffff8182c043: adjust_for_msb_right_quirk (STB_LOCAL)
ffffffff820f9172-ffffffff820f9223: adjust_for_msb_right_quirk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/packing.c (0)
Location: lib/packing.c:33
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff8187db40-ffffffff8187dc23: adjust_for_msb_right_quirk (STB_LOCAL)
ffffffff821d72df-ffffffff821d7390: adjust_for_msb_right_quirk.cold (STB_LOCAL)
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
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffff8000106422a8)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffff8000106422a8-ffff800010642350: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (c07e7cd0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
c07e7cd0-c07e7e00: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (c0000000007ed0a0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
c0000000007ed0a0-c0000000007ed178: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffe00046e64a)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffe00046e64a-ffffffe00046e6e2: adjust_for_msb_right_quirk (STB_LOCAL)
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
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff8152e0d0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff8152e0d0-ffffffff8152e171: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff8151e3b0)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff8151e3b0-ffffffff8151e451: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void adjust_for_msb_right_quirk(u64 *to_write, int *box_start_bit, int *box_end_bit, u8 *box_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/packing.c (ffffffff81543b40)
Location: lib/packing.c:45
Inline: False
Direct callers:
  - lib/packing.c:packing
  - lib/packing.c:packing
```
**Symbols:**

```
ffffffff81543b40-ffffffff81543be1: adjust_for_msb_right_quirk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
