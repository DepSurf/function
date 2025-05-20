# Function: <code>free_bucket_spinlocks</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff814cdcb0)
Location: lib/bucket_locks.c:47
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff814cdcb0-ffffffff814cdcbb: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff814e2580)
Location: lib/bucket_locks.c:50
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff814e2580-ffffffff814e258b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff8150e420)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff8150e420-ffffffff8150e42b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff8152c340)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff8152c340-ffffffff8152c34b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff8158fcb0)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff8158fcb0-ffffffff8158fcbb: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff815ac820)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff815ac820-ffffffff815ac82b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff815b7490)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff815b7490-ffffffff815b749b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff8161dac0)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff8161dac0-ffffffff8161dacb: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff816eb670)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff816eb670-ffffffff816eb681: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff817dbd90)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff817dbd90-ffffffff817dbda1: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff8181b150)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff8181b150-ffffffff8181b161: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff81860490)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff81860490-ffffffff818604a1: free_bucket_spinlocks (STB_GLOBAL)
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
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffff800010638380)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffff800010638380-ffff800010638394: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (c07ddbf0)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
c07ddbf0-c07ddc04: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (c0000000007de670)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
c0000000007de670-c0000000007de69c: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffe0004650a8)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffe0004650a8-ffffffe0004650c0: free_bucket_spinlocks (STB_GLOBAL)
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
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff81524920)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff81524920-ffffffff8152492b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff81514c00)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff81514c00-ffffffff81514c0b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff815209b0)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff815209b0-ffffffff815209bb: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_bucket_spinlocks(spinlock_t *locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bucket_locks.c (ffffffff8153a330)
Location: lib/bucket_locks.c:50
Inline: False
```
**Symbols:**

```
ffffffff8153a330-ffffffff8153a33b: free_bucket_spinlocks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
