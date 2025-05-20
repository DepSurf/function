# Function: <code>__up_read</code>

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
In kernel/locking/rwsem.c (ffffffff810c9f76)
Location: arch/x86/include/asm/rwsem.h:153
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ca0e9)
Location: arch/x86/include/asm/rwsem.h:153
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810ce8b6)
Location: arch/x86/include/asm/rwsem.h:164
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810cec38)
Location: arch/x86/include/asm/rwsem.h:164
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810d54f6)
Location: arch/x86/include/asm/rwsem.h:166
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810d5741)
Location: arch/x86/include/asm/rwsem.h:166
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
In kernel/locking/rwsem.c (ffffffff810d44c6)
Location: arch/x86/include/asm/rwsem.h:166
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810d46e3)
Location: arch/x86/include/asm/rwsem.h:166
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
In kernel/locking/rwsem.c (ffffffff810dc426)
Location: arch/x86/include/asm/rwsem.h:183
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810dc658)
Location: arch/x86/include/asm/rwsem.h:183
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
In kernel/locking/rwsem.c (ffffffff810e4a65)
Location: arch/x86/include/asm/rwsem.h:183
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810e4cb6)
Location: arch/x86/include/asm/rwsem.h:183
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
In kernel/locking/rwsem.c (ffffffff810f0095)
Location: arch/x86/include/asm/rwsem.h:183
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810f0296)
Location: arch/x86/include/asm/rwsem.h:183
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810f7f15)
Location: kernel/locking/rwsem.c:1399
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810f8760-ffffffff810f8794: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81103d45)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff811045a0-ffffffff811045d4: __up_read (STB_GLOBAL)
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
In kernel/locking/rwsem.c (0)
Location: kernel/locking/rwsem.c:1426
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (0)
Location: kernel/locking/rwsem.c:1287
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (0)
Location: kernel/locking/rwsem.c:1287
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8112d1d5)
Location: kernel/locking/rwsem.c:1294
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8114e4f5)
Location: kernel/locking/rwsem.c:1323
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8117d4d5)
Location: kernel/locking/rwsem.c:1340
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8118e1b5)
Location: kernel/locking/rwsem.c:1338
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff8119cb65)
Location: kernel/locking/rwsem.c:1338
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff8000101697f0)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffff800010169ed8-ffff800010169f54: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c03b5854)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
c03b61c4-c03b622c: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (c0000000001c10f0)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
c0000000001c1d90-c0000000001c1de8: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffe00010abca)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffe00010b06e-ffffffe00010b0a2: __up_read (STB_GLOBAL)
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
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fd055)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810fd8b0-ffffffff810fd8e4: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810ed265)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810edab0-ffffffff810edae4: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff810fa215)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff810faa70-ffffffff810faaa4: __up_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __up_read(struct rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff81105385)
Location: kernel/locking/rwsem.c:1429
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
```
**Symbols:**

```
ffffffff81105c40-ffffffff81105c74: __up_read (STB_GLOBAL)
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
