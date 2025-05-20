# Function: <code>console_on_rootfs</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/main.c (0)
Location: init/main.c:1464
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff81003c61-ffffffff81003c72: console_on_rootfs.cold (STB_LOCAL)
ffffffff81003a50-ffffffff81003a8a: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff82faf902)
Location: init/main.c:1485
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff82faf902-ffffffff82faf95d: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff831b9925)
Location: init/main.c:1507
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff831b9925-ffffffff831b9980: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83299d0d)
Location: init/main.c:1573
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff83299d0d-ffffffff83299d68: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83447f72)
Location: init/main.c:1579
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff83447f72-ffffffff83447fd7: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e61840)
Location: init/main.c:1589
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff83e61840-ffffffff83e618b8: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83681c60)
Location: init/main.c:1504
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff83681c60-ffffffff83681cd8: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void console_on_rootfs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838b0c90)
Location: init/main.c:1508
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
```
**Symbols:**

```
ffffffff838b0c90-ffffffff838b0d08: console_on_rootfs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
