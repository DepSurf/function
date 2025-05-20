# Function: <code>__hpet_calibrate</code>

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
In drivers/char/hpet.c (ffffffff8151a15b)
Location: drivers/char/hpet.c:783
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff8156ce52)
Location: drivers/char/hpet.c:783
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff815995c2)
Location: drivers/char/hpet.c:783
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff815ad555)
Location: drivers/char/hpet.c:784
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff81613f25)
Location: drivers/char/hpet.c:784
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff8164ddff)
Location: drivers/char/hpet.c:784
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff8166bf7f)
Location: drivers/char/hpet.c:782
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff816a1b42)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff816c48a2)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff81778f2a)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff81c08b1f)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff81bfa6be)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff81cfb168)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __hpet_calibrate(struct hpets *hpetp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81ec3659)
Location: drivers/char/hpet.c:743
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_alloc
```
**Symbols:**

```
ffffffff81ec3659-ffffffff81ec3750: __hpet_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __hpet_calibrate(struct hpets *hpetp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81a9a100)
Location: drivers/char/hpet.c:743
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_alloc
```
**Symbols:**

```
ffffffff81a9a100-ffffffff81a9a20e: __hpet_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __hpet_calibrate(struct hpets *hpetp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81ae5970)
Location: drivers/char/hpet.c:743
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_alloc
```
**Symbols:**

```
ffffffff81ae5970-ffffffff81ae5a7e: __hpet_calibrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __hpet_calibrate(struct hpets *hpetp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81b38d00)
Location: drivers/char/hpet.c:723
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_alloc
```
**Symbols:**

```
ffffffff81b38d00-ffffffff81b38e0e: __hpet_calibrate (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8168a2f2)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff81667d11)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff816b8562)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
In drivers/char/hpet.c (ffffffff816d2b32)
Location: drivers/char/hpet.c:778
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
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
