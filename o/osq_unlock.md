# Function: <code>osq_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810ca3f0)
Location: kernel/locking/osq_lock.c:185
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
```
**Symbols:**

```
ffffffff810ca3f0-ffffffff810ca46a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810ced80)
Location: kernel/locking/osq_lock.c:185
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810ced80-ffffffff810cedfa: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810d59c0)
Location: kernel/locking/osq_lock.c:192
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/mutex.c:mutex_optimistic_spin
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d59c0-ffffffff810d5a3a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810d4940)
Location: kernel/locking/osq_lock.c:192
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810d4940-ffffffff810d49ba: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810dc8c0)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810dc8c0-ffffffff810dc93a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810e4f00)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810e4f00-ffffffff810e4f7a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810f04e0)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
  - kernel/locking/rwsem-xadd.c:rwsem_down_write_failed
```
**Symbols:**

```
ffffffff810f04e0-ffffffff810f055a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810f8b60)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810f8b60-ffffffff810f8bda: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff81104970)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff81104970-ffffffff811049ea: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8110f720)
Location: kernel/locking/osq_lock.c:203
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110f720-ffffffff8110f79a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8110c8e0)
Location: kernel/locking/osq_lock.c:207
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110c8e0-ffffffff8110c95a: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8110e710)
Location: kernel/locking/osq_lock.c:207
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8110e710-ffffffff8110e78d: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8112dea0)
Location: kernel/locking/osq_lock.c:207
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8112dea0-ffffffff8112df1d: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8114eec0)
Location: kernel/locking/osq_lock.c:207
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8114eec0-ffffffff8114ef70: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8117e110)
Location: kernel/locking/osq_lock.c:207
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8117e110-ffffffff8117e1c0: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8118edb0)
Location: kernel/locking/osq_lock.c:207
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8118edb0-ffffffff8118ee60: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff8119d760)
Location: kernel/locking/osq_lock.c:210
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff8119d760-ffffffff8119d810: osq_unlock (STB_GLOBAL)
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
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffff80001016a730)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffff80001016a730-ffff80001016a874: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (c03b675c)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
c03b675c-c03b68a8: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (c0000000001c2450)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
c0000000001c2450-c0000000001c2540: osq_unlock (STB_GLOBAL)
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
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810fdc80)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810fdc80-ffffffff810fdcfa: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810ede80)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810ede80-ffffffff810edefa: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff810fae40)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff810fae40-ffffffff810faeba: osq_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void osq_unlock(struct optimistic_spin_queue *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/osq_lock.c (ffffffff81106010)
Location: kernel/locking/osq_lock.c:206
Inline: False
Direct callers:
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
**Symbols:**

```
ffffffff81106010-ffffffff8110608a: osq_unlock (STB_GLOBAL)
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
