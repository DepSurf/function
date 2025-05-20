# Function: <code>additional_memory_resource</code>

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
In drivers/xen/balloon.c (ffffffff814c68e9)
Location: drivers/xen/balloon.c:250
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff815170cd)
Location: drivers/xen/balloon.c:262
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff815434ad)
Location: drivers/xen/balloon.c:259
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff8155733d)
Location: drivers/xen/balloon.c:260
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff815bb36d)
Location: drivers/xen/balloon.c:275
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff815f3a38)
Location: drivers/xen/balloon.c:275
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff8160ea38)
Location: drivers/xen/balloon.c:254
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff8164283c)
Location: drivers/xen/balloon.c:251
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff81664dec)
Location: drivers/xen/balloon.c:249
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct resource *additional_memory_resource(phys_addr_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:248
Inline: False
Direct callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff817140d0-ffffffff81714184: additional_memory_resource (STB_LOCAL)
ffffffff81714bd1-ffffffff81714c11: additional_memory_resource.cold (STB_LOCAL)
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
In drivers/xen/balloon.c (ffffffff817310fc)
Location: drivers/xen/balloon.c:247
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff81714a7c)
Location: drivers/xen/balloon.c:247
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff8179193c)
Location: drivers/xen/balloon.c:252
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff818c9d56)
Location: drivers/xen/balloon.c:254
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81a1b006)
Location: drivers/xen/balloon.c:254
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81a641b6)
Location: drivers/xen/balloon.c:236
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81ab69ff)
Location: drivers/xen/balloon.c:235
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffff80001082ebf0)
Location: drivers/xen/balloon.c:249
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81658c2c)
Location: drivers/xen/balloon.c:249
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
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
In drivers/xen/balloon.c (ffffffff8167323c)
Location: drivers/xen/balloon.c:249
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
