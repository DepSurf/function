# Function: <code>irq_supports_nmi</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d489)
Location: kernel/irq/manage.c:1204
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffff8110b290-ffffffff8110b2c2: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119879)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffff811173c0-ffffffff811173f2: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81125139)
Location: kernel/irq/manage.c:1280
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff81120f99)
Location: kernel/irq/manage.c:1354
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff81121279)
Location: kernel/irq/manage.c:1354
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff811417f9)
Location: kernel/irq/manage.c:1378
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff81165249)
Location: kernel/irq/manage.c:1422
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff811990f9)
Location: kernel/irq/manage.c:1414
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff811aadd6)
Location: kernel/irq/manage.c:1420
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
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
In kernel/irq/manage.c (ffffffff811ba9e6)
Location: kernel/irq/manage.c:1422
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_nmi
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c57c)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffff8000101791a8-ffff8000101791f8: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (c03cd4cc)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
c03cafc0-c03cb000: irq_supports_nmi.part.0 (STB_LOCAL)
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
In kernel/irq/manage.c (c0000000001d71e4)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffe000115c1e)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffe0001141b6-ffffffe0001141f6: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffff81111e59)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffff8110f9a0-ffffffff8110f9d2: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102b89)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffff811006e0-ffffffff81100712: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110fd49)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffff8110d890-ffffffff8110d8c2: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111b279)
Location: kernel/irq/manage.c:1197
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:request_nmi
```
**Symbols:**

```
ffffffff81118df0-ffffffff81118e22: irq_supports_nmi.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
