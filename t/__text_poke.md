# Function: <code>__text_poke</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_kgdb
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff81039700-ffffffff81039b8f: __text_poke (STB_LOCAL)
ffffffff8103a588-ffffffff8103a59b: __text_poke.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81039ed0)
Location: arch/x86/kernel/alternative.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_kgdb
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff81039ed0-ffffffff8103a364: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103cb40)
Location: arch/x86/kernel/alternative.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8103cb40-ffffffff8103cfd8: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d000)
Location: arch/x86/kernel/alternative.c:855
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8103d000-ffffffff8103d455: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103e810)
Location: arch/x86/kernel/alternative.c:776
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8103e810-ffffffff8103ec8b: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81044580)
Location: arch/x86/kernel/alternative.c:776
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff81044580-ffffffff810449fb: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__text_poke(text_poke_f *func, void *addr, const void *src, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104cbc0)
Location: arch/x86/kernel/alternative.c:1082
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8104cbc0-ffffffff8104d021: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__text_poke(text_poke_f *func, void *addr, const void *src, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81058fd0)
Location: arch/x86/kernel/alternative.c:1545
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy_locked
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff81058fd0-ffffffff81059431: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__text_poke(text_poke_f *func, void *addr, const void *src, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105a580)
Location: arch/x86/kernel/alternative.c:1770
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy_locked
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8105a580-ffffffff8105a9dc: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__text_poke(text_poke_f *func, void *addr, const void *src, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810617d0)
Location: arch/x86/kernel/alternative.c:1860
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_set
  - arch/x86/kernel/alternative.c:text_poke_copy_locked
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff810617d0-ffffffff81061c95: __text_poke (STB_LOCAL)
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
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a030)
Location: arch/x86/kernel/alternative.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_kgdb
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8103a030-ffffffff8103a4c4: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81029910)
Location: arch/x86/kernel/alternative.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_kgdb
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff81029910-ffffffff81029cd8: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81039e90)
Location: arch/x86/kernel/alternative.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_kgdb
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff81039e90-ffffffff8103a324: __text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__text_poke(void *addr, const void *opcode, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ae90)
Location: arch/x86/kernel/alternative.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_bp_batch
  - arch/x86/kernel/alternative.c:text_poke_kgdb
  - arch/x86/kernel/alternative.c:alternatives_enable_smp
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
**Symbols:**

```
ffffffff8103ae90-ffffffff8103b322: __text_poke (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>text_poke_f *func</code>
</li>
<li>
<b>Param added. </b>
<code>const void *src</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *opcode</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, opcode, len</code> ➡️ <code>func, addr, src, len</code>
</li>
</ul>
</details>
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
