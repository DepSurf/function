# Function: <code>audit_init_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81129b20)
Location: kernel/audit_watch.c:171
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81129b20-ffffffff81129b7d: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81131cd0)
Location: kernel/audit_watch.c:172
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81131cd0-ffffffff81131d2d: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113ba30)
Location: kernel/audit_watch.c:172
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff8113ba30-ffffffff8113ba8d: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113d0e0)
Location: kernel/audit_watch.c:173
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff8113d0e0-ffffffff8113d13a: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81149ea0)
Location: kernel/audit_watch.c:173
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81149ea0-ffffffff81149efa: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811588a0)
Location: kernel/audit_watch.c:173
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff811588a0-ffffffff811588fa: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811657c0)
Location: kernel/audit_watch.c:173
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff811657c0-ffffffff8116581a: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81172330)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81172330-ffffffff8117238a: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117e1e0)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff8117e1e0-ffffffff8117e23a: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8119183b)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118e9eb)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118f81b)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b86fb)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811eb62b)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81231a2b)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff812486bb)
Location: kernel/audit_watch.c:160
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81262330)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81262330-ffffffff812623d3: audit_init_watch (STB_LOCAL)
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
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffff8000101f3058)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffff8000101f3058-ffff8000101f30c8: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0433574)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
c0433574-c04335d4: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c000000000267b00)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
c000000000267b00-c000000000267ba8: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffe0001665b4)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffe0001665b4-ffffffe000166612: audit_init_watch (STB_LOCAL)
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
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81176800)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81176800-ffffffff8117685a: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811699a0)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff811699a0-ffffffff811699fa: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811745d0)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff811745d0-ffffffff8117462a: audit_init_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct audit_watch *audit_init_watch(char *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81181eb0)
Location: kernel/audit_watch.c:160
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
**Symbols:**

```
ffffffff81181eb0-ffffffff81181f0a: audit_init_watch (STB_LOCAL)
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
