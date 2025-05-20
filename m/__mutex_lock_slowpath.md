# Function: <code>__mutex_lock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mutex_lock_slowpath(atomic_t *lock_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81822220)
Location: kernel/locking/mutex.c:816
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81822220-ffffffff81822345: __mutex_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mutex_lock_slowpath(atomic_t *lock_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189c680)
Location: kernel/locking/mutex.c:820
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff8189c680-ffffffff8189c7a8: __mutex_lock_slowpath (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d0620)
Location: kernel/locking/mutex.c:954
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff818d0620-ffffffff818d08bc: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81908050)
Location: kernel/locking/mutex.c:1129
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81908050-ffffffff81908065: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81992130)
Location: kernel/locking/mutex.c:1129
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81992130-ffffffff81992145: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819eeef0)
Location: kernel/locking/mutex.c:1153
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff819eeef0-ffffffff819eef05: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2a230)
Location: kernel/locking/mutex.c:1331
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81a2a230-ffffffff81a2a245: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9a9b0)
Location: kernel/locking/mutex.c:1336
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81a9a9b0-ffffffff81a9a9c5: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad2300)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81ad2300-ffffffff81ad2315: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bca4e0)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff81bca4e0-ffffffff81bca4f5: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c43340)
Location: kernel/locking/mutex.c:1365
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff81c43340-ffffffff81c43355: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c34a00)
Location: kernel/locking/mutex.c:1363
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff81c34a00-ffffffff81c34a15: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d53290)
Location: kernel/locking/mutex.c:977
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff81d53290-ffffffff81d532a5: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f24b80)
Location: kernel/locking/mutex.c:1033
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff81f24b80-ffffffff81f24b9f: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820d0100)
Location: kernel/locking/mutex.c:1033
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff820d0100-ffffffff820d011f: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff821538c0)
Location: kernel/locking/mutex.c:1033
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff821538c0-ffffffff821538df: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82236700)
Location: kernel/locking/mutex.c:1038
Inline: False
Direct callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_io
```
**Symbols:**

```
ffffffff82236700-ffffffff8223671f: __mutex_lock_slowpath (STB_LOCAL)
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
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da35f0)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffff800010da35f0-ffff800010da3620: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9c85c)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
c0e9c85c-c0e9c87c: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5be0)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
c000000000ee5be0-c000000000ee5bf8: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c7442)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffe0008c7442-ffffffe0008c746e: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a71170)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81a71170-ffffffff81a71185: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2d560)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81a2d560-ffffffff81a2d575: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81add580)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81add580-ffffffff81add595: __mutex_lock_slowpath (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __mutex_lock_slowpath(struct mutex *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae9140)
Location: kernel/locking/mutex.c:1362
Inline: False
Direct callers:
  - kernel/locking/mutex.c:mutex_lock
```
**Symbols:**

```
ffffffff81ae9140-ffffffff81ae9155: __mutex_lock_slowpath (STB_LOCAL)
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
<code>struct mutex *lock</code>
</li>
<li>
<b>Param removed. </b>
<code>atomic_t *lock_count</code>
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
