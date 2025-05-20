# Function: <code>sk_free_unlock_clone</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b5400)
Location: net/core/sock.c:1740
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff817b5400-ffffffff817b542f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182d880)
Location: net/core/sock.c:1751
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff8182d880-ffffffff8182d8af: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81877ef7)
Location: net/core/sock.c:1771
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81877c20-ffffffff81877c4f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818983d7)
Location: net/core/sock.c:1767
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81898100-ffffffff8189812f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e296b)
Location: net/core/sock.c:1899
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff818e2660-ffffffff818e268f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914b3f)
Location: net/core/sock.c:1912
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81914830-ffffffff8191485f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e6780)
Location: net/core/sock.c:2009
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff819e6780-ffffffff819e67db: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5dd0)
Location: net/core/sock.c:2001
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff819e5dd0-ffffffff819e5e2b: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cc3a0)
Location: net/core/sock.c:2030
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff819cc3a0-ffffffff819cc3fb: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7b9f0)
Location: net/core/sock.c:2154
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81a7b9f0-ffffffff81a7ba4b: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bef7a0)
Location: net/core/sock.c:2289
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81bef7a0-ffffffff81bef823: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9c730)
Location: net/core/sock.c:2368
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81d9c730-ffffffff81d9c7b3: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0af90)
Location: net/core/sock.c:2415
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81e0af90-ffffffff81e0b013: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec7980)
Location: net/core/sock.c:2395
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81ec7980-ffffffff81ec7a03: sk_free_unlock_clone (STB_GLOBAL)
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
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bad88c)
Location: net/core/sock.c:1912
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffff800010bad688-ffff800010bad6c4: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccb254)
Location: net/core/sock.c:1912
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
c0ccb254-c0ccb290: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c82f30)
Location: net/core/sock.c:1912
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
c000000000c82f30-c000000000c82fa4: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073f87c)
Location: net/core/sock.c:1912
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffe00073f87c-ffffffe00073f906: sk_free_unlock_clone (STB_GLOBAL)
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
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4b3f)
Location: net/core/sock.c:1912
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff818b4830-ffffffff818b485f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ea8f)
Location: net/core/sock.c:1912
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff8186e780-ffffffff8186e7af: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905b3f)
Location: net/core/sock.c:1912
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81905830-ffffffff8190585f: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sk_free_unlock_clone(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926b6f)
Location: net/core/sock.c:1912
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81926840-ffffffff81926871: sk_free_unlock_clone (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
