# Function: <code>coredump_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8126f108)
Location: fs/coredump.c:381
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8129a8ff)
Location: fs/coredump.c:406
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812af48f)
Location: fs/coredump.c:407
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812bc8cf)
Location: fs/coredump.c:409
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812e01bc)
Location: fs/coredump.c:410
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8130c3eb)
Location: fs/coredump.c:410
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81321c4b)
Location: fs/coredump.c:410
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81349a7e)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81361d1e)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813a7d60)
Location: fs/coredump.c:438
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813a7d60-ffffffff813a7e8f: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b8bf0)
Location: fs/coredump.c:448
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813b8bf0-ffffffff813b8d73: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813bfcf0)
Location: fs/coredump.c:448
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813bfcf0-ffffffff813bfe70: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8140fb20)
Location: fs/coredump.c:448
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8140fb20-ffffffff8140fc9f: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff814846d0)
Location: fs/coredump.c:392
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814846d0-ffffffff814848e3: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81517bd0)
Location: fs/coredump.c:399
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81517bd0-ffffffff81517daa: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8154f4c0)
Location: fs/coredump.c:401
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8154f4c0-ffffffff8154f6b2: coredump_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int coredump_wait(int exit_code, struct core_state *core_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81585300)
Location: fs/coredump.c:401
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81585300-ffffffff815854f2: coredump_wait (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffff80001042841c)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (c05f10a4)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (c0000000005385e0)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffe0002c6656)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8135a2fe)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8134afae)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81357dce)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8136b4ae)
Location: fs/coredump.c:436
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
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
