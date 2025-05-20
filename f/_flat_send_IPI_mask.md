# Function: <code>_flat_send_IPI_mask</code>

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
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a5d1)
Location: arch/x86/kernel/apic/apic_flat_64.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a610)
Location: arch/x86/kernel/apic/apic_flat_64.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff8105a610-ffffffff8105a647: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d420)
Location: arch/x86/kernel/apic/apic_flat_64.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff8105d420-ffffffff8105d457: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105cb40)
Location: arch/x86/kernel/apic/apic_flat_64.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff8105cb40-ffffffff8105cb77: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060880)
Location: arch/x86/kernel/apic/apic_flat_64.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff81060880-ffffffff810608b7: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063980)
Location: arch/x86/kernel/apic/apic_flat_64.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff81063980-ffffffff810639b7: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81069680)
Location: arch/x86/kernel/apic/apic_flat_64.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff81069680-ffffffff810696b7: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106ce80)
Location: arch/x86/kernel/apic/apic_flat_64.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff8106ce80-ffffffff8106ceb7: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e5e0)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8106e5e0-ffffffff8106e617: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075aa0)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81075aa0-ffffffff81075ada: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810760d0)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810760d0-ffffffff81076105: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076b60)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81076b60-ffffffff81076b9d: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084340)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81084340-ffffffff8108437d: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810944f0)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810944f0-ffffffff81094530: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9e40)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810a9e40-ffffffff810a9e94: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810ad200)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810ad200-ffffffff810ad254: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3d80)
Location: arch/x86/kernel/apic/apic_flat_64.c:31
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810b3d80-ffffffff810b3dd4: _flat_send_IPI_mask (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d580)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8106d580-ffffffff8106d5b7: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d9c0)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8105d9c0-ffffffff8105d9e1: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106da30)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8106da30-ffffffff8106da67: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fcb0)
Location: arch/x86/kernel/apic/apic_flat_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8106fcb0-ffffffff8106fce7: _flat_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
