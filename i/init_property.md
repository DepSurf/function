# Function: <code>init_property</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177ffea)
Location: drivers/extcon/extcon.c:350
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff8179e572)
Location: drivers/extcon/extcon.c:353
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff818156d2)
Location: drivers/extcon/extcon.c:341
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff8185f5c1)
Location: drivers/extcon/extcon.c:341
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff8187ef61)
Location: drivers/extcon/extcon.c:341
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff818c9577)
Location: drivers/extcon/extcon.c:333
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff818fb9c7)
Location: drivers/extcon/extcon.c:333
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d24d0)
Location: drivers/extcon/extcon.c:333
Inline: True
```
**Symbols:**

```
ffffffff819d24d0-ffffffff819d253d: init_property.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d20b0)
Location: drivers/extcon/extcon.c:333
Inline: True
```
**Symbols:**

```
ffffffff819d20b0-ffffffff819d211d: init_property.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b74cb)
Location: drivers/extcon/extcon.c:333
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a6609c)
Location: drivers/extcon/extcon.c:333
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_property(struct extcon_dev *edev, unsigned int id, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd6f50)
Location: drivers/extcon/extcon.c:333
Inline: False
```
**Symbols:**

```
ffffffff81bd6f50-ffffffff81bd7008: init_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_property(struct extcon_dev *edev, unsigned int id, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d83820)
Location: drivers/extcon/extcon.c:343
Inline: False
```
**Symbols:**

```
ffffffff81d83820-ffffffff81d838d8: init_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_property(struct extcon_dev *edev, unsigned int id, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df1c10)
Location: drivers/extcon/extcon.c:353
Inline: False
```
**Symbols:**

```
ffffffff81df1c10-ffffffff81df1cc8: init_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_property(struct extcon_dev *edev, unsigned int id, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea8260)
Location: drivers/extcon/extcon.c:353
Inline: False
```
**Symbols:**

```
ffffffff81ea8260-ffffffff81ea8318: init_property (STB_LOCAL)
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
In drivers/extcon/extcon.c (ffff800010b88bbc)
Location: drivers/extcon/extcon.c:333
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (c0c6d044)
Location: drivers/extcon/extcon.c:333
Inline: True
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
In drivers/extcon/extcon.c (c000000000c68200)
Location: drivers/extcon/extcon.c:333
Inline: True
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
In drivers/extcon/extcon.c (ffffffe0007316d0)
Location: drivers/extcon/extcon.c:333
Inline: True
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
In drivers/extcon/extcon.c (ffffffff8189ccf7)
Location: drivers/extcon/extcon.c:333
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ec3e7)
Location: drivers/extcon/extcon.c:333
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
In drivers/extcon/extcon.c (ffffffff8190d467)
Location: drivers/extcon/extcon.c:333
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_set_state
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
