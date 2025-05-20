# Function: <code>nvm_bb_chunk_scan</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699af9)
Location: drivers/lightnvm/core.c:833
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816d26a5)
Location: drivers/lightnvm/core.c:835
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816f6585)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvm_bb_chunk_scan(struct nvm_dev *dev, struct ppa_addr ppa, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817ae170)
Location: drivers/lightnvm/core.c:864
Inline: False
```
**Symbols:**

```
ffffffff817ae170-ffffffff817ae34a: nvm_bb_chunk_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvm_bb_chunk_scan(struct nvm_dev *dev, struct ppa_addr ppa, struct nvm_chk_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c2d00)
Location: drivers/lightnvm/core.c:859
Inline: False
```
**Symbols:**

```
ffffffff817c2d00-ffffffff817c2eda: nvm_bb_chunk_scan (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817a62c0)
Location: drivers/lightnvm/core.c:859
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff817a62c0-ffffffff817a64a1: nvm_bb_chunk_scan.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/lightnvm/core.c (ffff8000108dfc74)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (c09cef4c)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (c000000000973c9c)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffe000575b64)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816bbd75)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816ea245)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff81704a85)
Location: drivers/lightnvm/core.c:865
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
</ul>
