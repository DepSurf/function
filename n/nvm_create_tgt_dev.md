# Function: <code>nvm_create_tgt_dev</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d8729)
Location: drivers/lightnvm/core.c:123
Inline: True
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
In drivers/lightnvm/core.c (ffffffff8163f491)
Location: drivers/lightnvm/core.c:124
Inline: True
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
In drivers/lightnvm/core.c (ffffffff8167ac11)
Location: drivers/lightnvm/core.c:142
Inline: True
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
In drivers/lightnvm/core.c (ffffffff8169a557)
Location: drivers/lightnvm/core.c:142
Inline: True
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
In drivers/lightnvm/core.c (ffffffff816d2ed7)
Location: drivers/lightnvm/core.c:130
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff816f6db7)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nvm_tgt_dev *nvm_create_tgt_dev(struct nvm_dev *dev, u16 lun_begin, u16 lun_end, u16 op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817af9c0)
Location: drivers/lightnvm/core.c:132
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff817af9c0-ffffffff817afd92: nvm_create_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nvm_tgt_dev *nvm_create_tgt_dev(struct nvm_dev *dev, u16 lun_begin, u16 lun_end, u16 op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c4540)
Location: drivers/lightnvm/core.c:132
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff817c4540-ffffffff817c4912: nvm_create_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nvm_tgt_dev *nvm_create_tgt_dev(struct nvm_dev *dev, u16 lun_begin, u16 lun_end, u16 op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a7380)
Location: drivers/lightnvm/core.c:132
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff817a7380-ffffffff817a7779: nvm_create_tgt_dev (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffff8000108e0c98)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (c09cf7e0)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (c000000000974a58)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffe00057656a)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff816bc5a7)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff816eaa77)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
In drivers/lightnvm/core.c (ffffffff817052b7)
Location: drivers/lightnvm/core.c:132
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
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
</ul>
