# Function: <code>text_poke_flush</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d975)
Location: arch/x86/kernel/alternative.c:1293
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff8103d170-ffffffff8103d1c4: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103de65)
Location: arch/x86/kernel/alternative.c:1344
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff8103d650-ffffffff8103d6a4: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103f895)
Location: arch/x86/kernel/alternative.c:1265
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff8103ee90-ffffffff8103eee4: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810456a5)
Location: arch/x86/kernel/alternative.c:1265
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff81044c00-ffffffff81044c8a: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104e185)
Location: arch/x86/kernel/alternative.c:1657
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff8104d2e0-ffffffff8104d37e: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105b035)
Location: arch/x86/kernel/alternative.c:2160
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff81059750-ffffffff810597ee: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105c575)
Location: arch/x86/kernel/alternative.c:2395
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff8105ad00-ffffffff8105ad9e: text_poke_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void text_poke_flush(void *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81063635)
Location: arch/x86/kernel/alternative.c:2485
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_finish
  - arch/x86/kernel/alternative.c:text_poke_finish
Direct callers:
  - arch/x86/kernel/alternative.c:text_poke_queue
```
**Symbols:**

```
ffffffff81061fc0-ffffffff8106205e: text_poke_flush (STB_LOCAL)
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
