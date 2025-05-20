# Function: <code>percpu_free_rwsem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810ca230)
Location: kernel/locking/percpu-rwsem.c:27
Inline: False
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
```
**Symbols:**

```
ffffffff810ca230-ffffffff810ca25e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *brw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810cea10)
Location: kernel/locking/percpu-rwsem.c:27
Inline: False
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810cea10-ffffffff810cea3e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d5650)
Location: kernel/locking/percpu-rwsem.c:27
Inline: False
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810d5650-ffffffff810d567e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d4660)
Location: kernel/locking/percpu-rwsem.c:26
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810d4660-ffffffff810d468f: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810dc5d0)
Location: kernel/locking/percpu-rwsem.c:26
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810dc5d0-ffffffff810dc5ff: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810e4c20)
Location: kernel/locking/percpu-rwsem.c:26
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810e4c20-ffffffff810e4c4e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f0200)
Location: kernel/locking/percpu-rwsem.c:26
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810f0200-ffffffff810f022e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810f8870)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810f8870-ffffffff810f889e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff811046b0)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff811046b0-ffffffff811046de: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110f1b0)
Location: kernel/locking/percpu-rwsem.c:31
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8110f1b0-ffffffff8110f1e1: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110c370)
Location: kernel/locking/percpu-rwsem.c:31
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8110c370-ffffffff8110c3a1: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110e1b0)
Location: kernel/locking/percpu-rwsem.c:31
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8110e1b0-ffffffff8110e1e1: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8112d900)
Location: kernel/locking/percpu-rwsem.c:31
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8112d900-ffffffff8112d931: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8114e930)
Location: kernel/locking/percpu-rwsem.c:33
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8114e930-ffffffff8114e96d: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8117d9f0)
Location: kernel/locking/percpu-rwsem.c:33
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8117d9f0-ffffffff8117da2d: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8118e690)
Location: kernel/locking/percpu-rwsem.c:33
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8118e690-ffffffff8118e6cd: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8119d040)
Location: kernel/locking/percpu-rwsem.c:33
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_percpu_param_destroy
```
**Symbols:**

```
ffffffff8119d040-ffffffff8119d07d: percpu_free_rwsem (STB_GLOBAL)
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
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffff80001016a2f0)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffff80001016a2f0-ffff80001016a330: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c03b6410)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c03b6410-c03b644c: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (c0000000001c20c0)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c0000000001c20c0-c0000000001c2120: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffe00010b264)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffe00010b264-ffffffe00010b2a0: percpu_free_rwsem (STB_GLOBAL)
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
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fd9c0)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810fd9c0-ffffffff810fd9ee: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810edbc0)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810edbc0-ffffffff810edbee: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810fab80)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff810fab80-ffffffff810fabae: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void percpu_free_rwsem(struct percpu_rw_semaphore *sem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff81105d50)
Location: kernel/locking/percpu-rwsem.c:29
Inline: True
Direct callers:
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/super.c:destroy_super_work
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81105d50-ffffffff81105d7e: percpu_free_rwsem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct percpu_rw_semaphore *sem</code>
</li>
<li>
<b>Param removed. </b>
<code>struct percpu_rw_semaphore *brw</code>
</li>
</ul>
</details>
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
