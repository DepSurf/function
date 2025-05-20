# Function: <code>input_copy_abs</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void input_copy_abs(struct input_dev *dst, unsigned int dst_axis, const struct input_dev *src, unsigned int src_axis);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:553
Inline: False
```
**Symbols:**

```
ffffffff81eef0da-ffffffff81eef0fe: input_copy_abs.cold (STB_LOCAL)
ffffffff81b16cd0-ffffffff81b16d92: input_copy_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void input_copy_abs(struct input_dev *dst, unsigned int dst_axis, const struct input_dev *src, unsigned int src_axis);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca7240)
Location: drivers/input/input.c:528
Inline: False
```
**Symbols:**

```
ffffffff81ca7240-ffffffff81ca72ef: input_copy_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void input_copy_abs(struct input_dev *dst, unsigned int dst_axis, const struct input_dev *src, unsigned int src_axis);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d0eeb0)
Location: drivers/input/input.c:531
Inline: False
```
**Symbols:**

```
ffffffff81d0eeb0-ffffffff81d0ef5f: input_copy_abs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void input_copy_abs(struct input_dev *dst, unsigned int dst_axis, const struct input_dev *src, unsigned int src_axis);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc4bd0)
Location: drivers/input/input.c:531
Inline: False
```
**Symbols:**

```
ffffffff81dc4bd0-ffffffff81dc4c7f: input_copy_abs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
