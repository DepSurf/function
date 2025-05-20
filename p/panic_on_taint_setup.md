# Function: <code>panic_on_taint_setup</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff82cece71)
Location: kernel/panic.c:710
Inline: False
```
**Symbols:**

```
ffffffff82cece71-ffffffff82cecf30: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff82fd94cb)
Location: kernel/panic.c:711
Inline: False
```
**Symbols:**

```
ffffffff82fd94cb-ffffffff82fd958a: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff831e3e1f)
Location: kernel/panic.c:711
Inline: False
```
**Symbols:**

```
ffffffff831e3e1f-ffffffff831e3ede: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff832c79f7)
Location: kernel/panic.c:709
Inline: False
```
**Symbols:**

```
ffffffff832c79f7-ffffffff832c7abb: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8347a940)
Location: kernel/panic.c:729
Inline: False
```
**Symbols:**

```
ffffffff8347a940-ffffffff8347aa11: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff83ea52e0)
Location: kernel/panic.c:783
Inline: False
```
**Symbols:**

```
ffffffff83ea52e0-ffffffff83ea53db: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff836c9680)
Location: kernel/panic.c:782
Inline: False
```
**Symbols:**

```
ffffffff836c9680-ffffffff836c977b: panic_on_taint_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int panic_on_taint_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff838fa2d0)
Location: kernel/panic.c:787
Inline: False
```
**Symbols:**

```
ffffffff838fa2d0-ffffffff838fa3cb: panic_on_taint_setup (STB_LOCAL)
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
