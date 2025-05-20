# Function: <code>__down_read_trylock</code>

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
In kernel/locking/rwsem.c (ffffffff810c9ef9)
Location: arch/x86/include/asm/rwsem.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810ca285)
Location: arch/x86/include/asm/rwsem.h:80
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
In kernel/locking/rwsem.c (ffffffff810ce959)
Location: arch/x86/include/asm/rwsem.h:80
Inline: True
```
```
In kernel/locking/percpu-rwsem.c (ffffffff810cec15)
Location: arch/x86/include/asm/rwsem.h:80
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810d5599)
Location: arch/x86/include/asm/rwsem.h:80
Inline: True
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
In kernel/locking/rwsem.c (ffffffff810d4569)
Location: arch/x86/include/asm/rwsem.h:80
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
In kernel/locking/rwsem.c (ffffffff810dc4c9)
Location: arch/x86/include/asm/rwsem.h:96
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
In kernel/locking/rwsem.c (ffffffff810e4b05)
Location: arch/x86/include/asm/rwsem.h:96
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
In kernel/locking/rwsem.c (ffffffff810f0015)
Location: arch/x86/include/asm/rwsem.h:96
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810f7ad5)
Location: kernel/locking/rwsem.c:1339
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff81103905)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8110e455)
Location: kernel/locking/rwsem.c:1360
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8110b715)
Location: kernel/locking/rwsem.c:1235
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8110d535)
Location: kernel/locking/rwsem.c:1235
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8112cd85)
Location: kernel/locking/rwsem.c:1242
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8114e025)
Location: kernel/locking/rwsem.c:1274
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8117cf85)
Location: kernel/locking/rwsem.c:1287
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8118dc35)
Location: kernel/locking/rwsem.c:1276
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff8119c5e5)
Location: kernel/locking/rwsem.c:1276
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffff800010168f60)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (c03b57d0)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (c0000000001c1278)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffe00010a822)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810fcc15)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810ece25)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff810f9dd5)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
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
In kernel/locking/rwsem.c (ffffffff81104f45)
Location: kernel/locking/rwsem.c:1363
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_read_trylock
```
</details>
</li>
</ul>

## Differences
