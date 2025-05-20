# Function: <code>reset_simple_assert</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int reset_simple_assert(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (ffffffff81a479c0)
Location: drivers/reset/reset-simple.c:55
Inline: True
```
**Symbols:**

```
ffffffff81a479c0-ffffffff81a479df: reset_simple_assert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int reset_simple_assert(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (ffffffff81a91b60)
Location: drivers/reset/reset-simple.c:55
Inline: True
```
**Symbols:**

```
ffffffff81a91b60-ffffffff81a91b7f: reset_simple_assert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int reset_simple_assert(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (ffffffff81ae44f0)
Location: drivers/reset/reset-simple.c:54
Inline: True
```
**Symbols:**

```
ffffffff81ae44f0-ffffffff81ae450f: reset_simple_assert (STB_LOCAL)
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
int reset_simple_assert(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (ffff80001084df40)
Location: drivers/reset/reset-simple.c:55
Inline: False
```
**Symbols:**

```
ffff80001084df40-ffff80001084df78: reset_simple_assert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reset_simple_assert(struct reset_controller_dev *rcdev, long unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (c095a08c)
Location: drivers/reset/reset-simple.c:55
Inline: False
```
**Symbols:**

```
c095a08c-c095a0ac: reset_simple_assert (STB_LOCAL)
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
