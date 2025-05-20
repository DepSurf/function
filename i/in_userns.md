# Function: <code>in_userns</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113de46)
Location: kernel/user_namespace.c:1231
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff8113f340-ffffffff8113f36e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114c806)
Location: kernel/user_namespace.c:1228
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff8114dc70-ffffffff8114dc9e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81159426)
Location: kernel/user_namespace.c:1232
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff8115a940-ffffffff8115a96e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81165b66)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81166ff0-ffffffff8116701e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81171a26)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81172eb0-ffffffff81172ede: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81183846)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff81184d10-ffffffff81184d3e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81180776)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff81181d60-ffffffff81181d8e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811817d6)
Location: kernel/user_namespace.c:1285
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff81182eb0-ffffffff81182ede: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a96f6)
Location: kernel/user_namespace.c:1301
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff811aaf60-ffffffff811aaf8e: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811daae6)
Location: kernel/user_namespace.c:1306
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff811dc680-ffffffff811dc6b6: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81220176)
Location: kernel/user_namespace.c:1306
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff81221f80-ffffffff81221fb6: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812363e6)
Location: kernel/user_namespace.c:1306
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff81238430-ffffffff81238466: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81250066)
Location: kernel/user_namespace.c:1309
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
**Symbols:**

```
ffffffff81252100-ffffffff81252136: in_userns (STB_GLOBAL)
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
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e5808)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffff8000101e6fe0-ffff8000101e7034: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0425f98)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
c0427544-c0427588: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000255be8)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
c0000000002577e0-c000000000257820: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015b2ea)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffe00015c676-ffffffe00015c6ba: in_userns (STB_GLOBAL)
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
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a046)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff8116b4d0-ffffffff8116b4fe: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d246)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff8115e6d0-ffffffff8115e6fe: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81167e16)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff811692a0-ffffffff811692ce: in_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool in_userns(const struct user_namespace *ancestor, const struct user_namespace *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811754f6)
Location: kernel/user_namespace.c:1226
Inline: True
Inline callers:
  - kernel/user_namespace.c:current_in_userns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
**Symbols:**

```
ffffffff81176990-ffffffff811769be: in_userns (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
