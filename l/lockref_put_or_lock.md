# Function: <code>lockref_put_or_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff813f7cc0)
Location: lib/lockref.c:132
Inline: True
Direct callers:
  - fs/dcache.c:dput
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff813f7cc0-ffffffff813f7d38: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8143eb60)
Location: lib/lockref.c:132
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8143eb60-ffffffff8143ebe2: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8145bbb0)
Location: lib/lockref.c:132
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8145bbb0-ffffffff8145bc32: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff814610a0)
Location: lib/lockref.c:132
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff814610a0-ffffffff81461120: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8148cf70)
Location: lib/lockref.c:133
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff8148cf70-ffffffff8148cfec: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff814c1da0)
Location: lib/lockref.c:161
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff814c1da0-ffffffff814c1e1c: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff814d6490)
Location: lib/lockref.c:161
Inline: True
Direct callers:
  - fs/dcache.c:shrink_dentry_list
```
**Symbols:**

```
ffffffff814d6490-ffffffff814d650c: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81502330)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81502330-ffffffff815023b4: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81520240)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81520240-ffffffff815202c4: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81583100)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81583100-ffffffff81583186: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8159ff80)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8159ff80-ffffffff815a0006: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815a6d70)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff815a6d70-ffffffff815a6df3: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8160fcb0)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8160fcb0-ffffffff8160fd33: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff816dc250)
Location: lib/lockref.c:138
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff816dc250-ffffffff816dc2cd: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff817cbf00)
Location: lib/lockref.c:137
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff817cbf00-ffffffff817cbf7b: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8180a310)
Location: lib/lockref.c:137
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8180a310-ffffffff8180a39b: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81850b20)
Location: lib/lockref.c:137
Inline: False
```
**Symbols:**

```
ffffffff81850b20-ffffffff81850b9b: lockref_put_or_lock (STB_GLOBAL)
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
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffff800010629198)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffff800010629198-ffff800010629288: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (c07d07fc)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
c07d07fc-c07d0900: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (c0000000007cadd0)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
c0000000007cadd0-c0000000007caee8: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffe00045a3be)
Location: lib/lockref.c:164
Inline: False
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffe00045a3be-ffffffe00045a42c: lockref_put_or_lock (STB_GLOBAL)
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
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81518820)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81518820-ffffffff815188a4: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff81508b20)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff81508b20-ffffffff81508ba4: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff815148b0)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff815148b0-ffffffff81514934: lockref_put_or_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int lockref_put_or_lock(struct lockref *lockref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lockref.c (ffffffff8152df70)
Location: lib/lockref.c:164
Inline: True
Direct callers:
  - fs/dcache.c:dput_to_list
  - fs/dcache.c:dput
```
**Symbols:**

```
ffffffff8152df70-ffffffff8152dff2: lockref_put_or_lock (STB_GLOBAL)
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
