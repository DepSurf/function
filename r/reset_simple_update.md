# Function: <code>reset_simple_update</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_simple_update(struct reset_controller_dev *rcdev, long unsigned int id, bool assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/reset-simple.c (0)
Location: drivers/reset/reset-simple.c:31
Inline: False
```
**Symbols:**

```
ffffffff81a478d0-ffffffff81a4797f: reset_simple_update (STB_LOCAL)
ffffffff82094f68-ffffffff82094f8e: reset_simple_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_simple_update(struct reset_controller_dev *rcdev, long unsigned int id, bool assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/reset-simple.c (0)
Location: drivers/reset/reset-simple.c:31
Inline: False
```
**Symbols:**

```
ffffffff81a91a70-ffffffff81a91b1f: reset_simple_update (STB_LOCAL)
ffffffff82115d86-ffffffff82115dac: reset_simple_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_simple_update(struct reset_controller_dev *rcdev, long unsigned int id, bool assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/reset-simple.c (0)
Location: drivers/reset/reset-simple.c:30
Inline: False
```
**Symbols:**

```
ffffffff81ae4400-ffffffff81ae44af: reset_simple_update (STB_LOCAL)
ffffffff821f3a8d-ffffffff821f3ab3: reset_simple_update.cold (STB_LOCAL)
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
int reset_simple_update(struct reset_controller_dev *rcdev, long unsigned int id, bool assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (ffff80001084ddf8)
Location: drivers/reset/reset-simple.c:31
Inline: False
Direct callers:
  - drivers/reset/reset-simple.c:reset_simple_deassert
  - drivers/reset/reset-simple.c:reset_simple_assert
```
**Symbols:**

```
ffff80001084ddf8-ffff80001084df04: reset_simple_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reset_simple_update(struct reset_controller_dev *rcdev, long unsigned int id, bool assert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/reset-simple.c (c0959fe0)
Location: drivers/reset/reset-simple.c:31
Inline: False
Direct callers:
  - drivers/reset/reset-simple.c:reset_simple_deassert
  - drivers/reset/reset-simple.c:reset_simple_assert
```
**Symbols:**

```
c0959fe0-c095a06c: reset_simple_update (STB_LOCAL)
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
