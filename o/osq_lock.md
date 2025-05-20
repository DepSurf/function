# Function: <code>osq_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810ca2f0)
Location: kernel/locking/osq_lock.c:84
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
**Symbols:**

```
ffffffff810ca2f0-ffffffff810ca3e8: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810cec80)
Location: kernel/locking/osq_lock.c:84
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810cec80-ffffffff810ced78: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810d58a0)
Location: kernel/locking/osq_lock.c:89
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d58a0-ffffffff810d59b5: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810d4820)
Location: kernel/locking/osq_lock.c:89
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d4820-ffffffff810d4937: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810dc7a0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810dc7a0-ffffffff810dc8b1: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810e4df0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810e4df0-ffffffff810e4efd: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810f03d0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810f03d0-ffffffff810f04dd: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810f8a40)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810f8a40-ffffffff810f8b53: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff81104850)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff81104850-ffffffff81104963: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8110f600)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110f600-ffffffff8110f712: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8110c7c0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110c7c0-ffffffff8110c8d2: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8110e5f0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110e5f0-ffffffff8110e702: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8112dd50)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8112dd50-ffffffff8112dea0: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8114ed60)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8114ed60-ffffffff8114eeb4: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8117dfa0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8117dfa0-ffffffff8117e100: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8118ec40)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8118ec40-ffffffff8118eda0: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8119d5f0)
Location: kernel/locking/osq_lock.c:93
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8119d5f0-ffffffff8119d746: osq_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffff80001016a560)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffff80001016a560-ffff80001016a72c: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (c03b6518)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
c03b6518-c03b675c: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (c0000000001c2230)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
c0000000001c2230-c0000000001c2450: osq_lock (STB_GLOBAL)
```
</details>
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
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810fdb60)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810fdb60-ffffffff810fdc73: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810edd60)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810edd60-ffffffff810ede73: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810fad20)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810fad20-ffffffff810fae33: osq_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool osq_lock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff81105ef0)
Location: kernel/locking/osq_lock.c:90
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81106003: osq_lock (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
