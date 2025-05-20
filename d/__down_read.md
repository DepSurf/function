# Function: <code>__down_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81822832)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ca0da)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8189cce2)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810cea9a)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff818d1bc2)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810d572f)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81908d92)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810d46d1)
Location: arch/x86/include/asm/rwsem.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81992e52)
Location: arch/x86/include/asm/rwsem.h:81
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810dc64a)
Location: arch/x86/include/asm/rwsem.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff819ef432)
Location: arch/x86/include/asm/rwsem.h:81
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810e4c9a)
Location: arch/x86/include/asm/rwsem.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a2a772)
Location: arch/x86/include/asm/rwsem.h:81
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810f027a)
Location: arch/x86/include/asm/rwsem.h:81
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a9b4e3)
Location: kernel/locking/rwsem.c:1317
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff810f86e0-ffffffff810f8757: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81ad2e33)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81104520-ffffffff81104597: __down_read (STB_GLOBAL)
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
In kernel/locking/rwsem.c (ffffffff81bcae53)
Location: kernel/locking/rwsem.c:1338
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff81c43c43)
Location: kernel/locking/rwsem.c:1220
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff81c35a93)
Location: kernel/locking/rwsem.c:1220
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff81d54293)
Location: kernel/locking/rwsem.c:1227
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff81f25452)
Location: kernel/locking/rwsem.c:1259
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff820d0d92)
Location: kernel/locking/rwsem.c:1272
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff82155122)
Location: kernel/locking/rwsem.c:1261
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
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
In kernel/locking/rwsem.c (ffffffff82237f62)
Location: kernel/locking/rwsem.c:1261
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010da541c)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffff800010169e28-ffff800010169ed8: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0e9d4e4)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
c03b60c0-c03b61c4: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c000000000ee7bfc)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
c0000000001c1ce0-c0000000001c1d88: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe0008c7f28)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffe00010afea-ffffffe00010b06e: __down_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a71ca3)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff810fd830-ffffffff810fd8a7: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81a2e073)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff810eda30-ffffffff810edaa7: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81ade0b3)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff810fa9f0-ffffffff810faa67: __down_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __down_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81aea565)
Location: kernel/locking/rwsem.c:1341
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read
  - kernel/locking/rwsem.c:down_read
```
**Symbols:**

```
ffffffff81105bc0-ffffffff81105c37: __down_read (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
