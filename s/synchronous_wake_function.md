# Function: <code>synchronous_wake_function</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cdc40)
Location: mm/shmem.c:1888
Inline: False
```
**Symbols:**

```
ffffffff811cdc40-ffffffff811cdc70: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d67d0)
Location: mm/shmem.c:1922
Inline: False
```
**Symbols:**

```
ffffffff811d67d0-ffffffff811d6800: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ebcf0)
Location: mm/shmem.c:1933
Inline: False
```
**Symbols:**

```
ffffffff811ebcf0-ffffffff811ebd20: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120d480)
Location: mm/shmem.c:1952
Inline: False
```
**Symbols:**

```
ffffffff8120d480-ffffffff8120d4b0: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81220050)
Location: mm/shmem.c:1914
Inline: False
```
**Symbols:**

```
ffffffff81220050-ffffffff81220080: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122f800)
Location: mm/shmem.c:1976
Inline: False
```
**Symbols:**

```
ffffffff8122f800-ffffffff8122f830: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d9d0)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffffffff8123d9d0-ffffffff8123da00: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126af20)
Location: mm/shmem.c:1969
Inline: False
```
**Symbols:**

```
ffffffff8126af20-ffffffff8126af53: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812758c0)
Location: mm/shmem.c:2031
Inline: False
```
**Symbols:**

```
ffffffff812758c0-ffffffff812758f3: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127abe0)
Location: mm/shmem.c:2033
Inline: False
```
**Symbols:**

```
ffffffff8127abe0-ffffffff8127ac13: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b8c40)
Location: mm/shmem.c:2044
Inline: False
```
**Symbols:**

```
ffffffff812b8c40-ffffffff812b8c73: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813149d0)
Location: mm/shmem.c:2043
Inline: False
```
**Symbols:**

```
ffffffff813149d0-ffffffff81314a0f: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813888c0)
Location: mm/shmem.c:2060
Inline: False
```
**Symbols:**

```
ffffffff813888c0-ffffffff813888ff: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813baaf0)
Location: mm/shmem.c:2090
Inline: False
```
**Symbols:**

```
ffffffff813baaf0-ffffffff813bab2f: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e5130)
Location: mm/shmem.c:2143
Inline: False
```
**Symbols:**

```
ffffffff813e5130-ffffffff813e516f: synchronous_wake_function (STB_LOCAL)
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
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102cf400)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffff8000102cf400-ffff8000102cf464: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04f8c68)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
c04f8c68-c04f8ca4: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038cd80)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
c00000000038cd80-c00000000038cddc: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ecce0)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffffffe0001ecce0-ffffffe0001ecd32: synchronous_wake_function (STB_LOCAL)
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
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236020)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffffffff81236020-ffffffff81236050: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81229080)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffffffff81229080-ffffffff812290b0: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81233dc0)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffffffff81233dc0-ffffffff81233df0: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int synchronous_wake_function(wait_queue_entry_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243390)
Location: mm/shmem.c:1991
Inline: False
```
**Symbols:**

```
ffffffff81243390-ffffffff812433c0: synchronous_wake_function (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>wait_queue_t *wait</code> ➡️ <code>wait_queue_entry_t *wait</code>
</li>
</ul>
</details>
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
