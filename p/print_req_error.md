# Function: <code>print_req_error</code>

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
In block/blk-core.c (ffffffff81425943)
Location: block/blk-core.c:178
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff81450acf)
Location: block/blk-core.c:178
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff81483dbd)
Location: block/blk-core.c:251
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff8149f37d)
Location: block/blk-core.c:169
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff814cd479)
Location: block/blk-core.c:207
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff814e653d)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (0)
Location: block/blk-core.c:218
Inline: True
Direct callers:
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
ffffffff81542eb0-ffffffff81542eee: print_req_error.constprop.0 (STB_LOCAL)
ffffffff81546224-ffffffff815462b6: print_req_error.constprop.0.cold (STB_LOCAL)
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
In block/blk-core.c (0)
Location: block/blk-core.c:221
Inline: True
Direct callers:
  - block/blk-core.c:blk_update_request
```
**Symbols:**

```
ffffffff8155f730-ffffffff8155f76e: print_req_error.constprop.0 (STB_LOCAL)
ffffffff81bf257b-ffffffff81bf260d: print_req_error.constprop.0.cold (STB_LOCAL)
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
In block/blk-core.c (ffffffff81568f37)
Location: block/blk-core.c:222
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff815cd1e3)
Location: block/blk-core.c:217
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
</details>
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
In block/blk-core.c (ffff8000105e3bf4)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (c0791054)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (c000000000777758)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffe000425758)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff814deb1d)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff814cf4bd)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff814dabad)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
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
In block/blk-core.c (ffffffff814f392d)
Location: block/blk-core.c:210
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
</details>
</li>
</ul>

## Differences
