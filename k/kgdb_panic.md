# Function: <code>kgdb_panic</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811850f0)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff811850f0-ffffffff81185135: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81199260)
Location: kernel/debug/debug_core.c:949
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81199260-ffffffff811992a5: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81196590)
Location: kernel/debug/debug_core.c:988
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81196590-ffffffff811965d5: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81197540)
Location: kernel/debug/debug_core.c:987
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81197540-ffffffff81197585: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811c12b0)
Location: kernel/debug/debug_core.c:984
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff811c12b0-ffffffff811c12f5: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f48a0)
Location: kernel/debug/debug_core.c:1008
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff811f48a0-ffffffff811f490f: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123b800)
Location: kernel/debug/debug_core.c:996
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff8123b800-ffffffff8123b86f: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81252810)
Location: kernel/debug/debug_core.c:996
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81252810-ffffffff8125287f: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126c660)
Location: kernel/debug/debug_core.c:996
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff8126c660-ffffffff8126c6e7: kgdb_panic (STB_GLOBAL)
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
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fad08)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffff8000101fad08-ffff8000101fad6c: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043ae08)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
c043ae08-c043ae78: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000272870)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
c000000000272870-c0000000002728f0: kgdb_panic (STB_GLOBAL)
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
In kernel/panic.c (0)
Location: include/linux/kgdb.h:333
Inline: True
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
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117d710)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff8117d710-ffffffff8117d755: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81170860)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81170860-ffffffff811708a5: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117b4e0)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff8117b4e0-ffffffff8117b525: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kgdb_panic(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81188e00)
Location: kernel/debug/debug_core.c:896
Inline: False
Direct callers:
  - kernel/panic.c:panic
```
**Symbols:**

```
ffffffff81188e00-ffffffff81188e45: kgdb_panic (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
