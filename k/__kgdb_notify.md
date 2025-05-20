# Function: <code>__kgdb_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81061600)
Location: arch/x86/kernel/kgdb.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81061600-ffffffff810616ce: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81061420)
Location: arch/x86/kernel/kgdb.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81061420-ffffffff810614ee: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810644d0)
Location: arch/x86/kernel/kgdb.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff810644d0-ffffffff8106459a: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81063400)
Location: arch/x86/kernel/kgdb.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81063400-ffffffff810634cf: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff81067580)
Location: arch/x86/kernel/kgdb.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81067580-ffffffff8106764f: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8106a180-ffffffff8106a20f: __kgdb_notify (STB_LOCAL)
ffffffff8106a698-ffffffff8106a6e0: __kgdb_notify.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8106ff10-ffffffff8106ff9f: __kgdb_notify (STB_LOCAL)
ffffffff81070428-ffffffff81070470: __kgdb_notify.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81074010-ffffffff8107409f: __kgdb_notify (STB_LOCAL)
ffffffff81074475-ffffffff810744bd: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81074fd0-ffffffff8107505f: __kgdb_notify (STB_LOCAL)
ffffffff81075445-ffffffff8107548d: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8107c1e0-ffffffff8107c26d: __kgdb_notify (STB_LOCAL)
ffffffff8107c651-ffffffff8107c699: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8107c0d0-ffffffff8107c15d: __kgdb_notify (STB_LOCAL)
ffffffff81bd7c3a-ffffffff81bd7c82: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8107d280-ffffffff8107d300: __kgdb_notify (STB_LOCAL)
ffffffff81bc9bed-ffffffff81bc9c32: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8108bba0-ffffffff8108bc20: __kgdb_notify (STB_LOCAL)
ffffffff81c9eafa-ffffffff81c9eb3f: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff8109c410-ffffffff8109c49c: __kgdb_notify (STB_LOCAL)
ffffffff81e4df00-ffffffff81e4df40: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810b3100)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff810b3100-ffffffff810b31cb: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810b6200)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff810b6200-ffffffff810b62cb: __kgdb_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kgdb.c (ffffffff810bd640)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff810bd640-ffffffff810bd70b: __kgdb_notify (STB_LOCAL)
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
In arch/arm64/kernel/kgdb.c (ffff8000100a72bc)
Location: arch/arm64/kernel/kgdb.c:274
Inline: True
Inline callers:
  - arch/arm64/kernel/kgdb.c:kgdb_notify
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
In arch/arm/kernel/kgdb.c (c0315738)
Location: arch/arm/kernel/kgdb.c:173
Inline: True
Inline callers:
  - arch/arm/kernel/kgdb.c:kgdb_notify
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81073fd0-ffffffff8107405f: __kgdb_notify (STB_LOCAL)
ffffffff81074445-ffffffff8107448d: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81064020-ffffffff810640af: __kgdb_notify (STB_LOCAL)
ffffffff81064475-ffffffff810644bd: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81073f80-ffffffff8107400f: __kgdb_notify (STB_LOCAL)
ffffffff810743f5-ffffffff8107443d: __kgdb_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __kgdb_notify(struct die_args *args, long unsigned int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kgdb.c (0)
Location: arch/x86/kernel/kgdb.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_notify
  - arch/x86/kernel/kgdb.c:kgdb_ll_trap
```
**Symbols:**

```
ffffffff81075fe0-ffffffff8107606f: __kgdb_notify (STB_LOCAL)
ffffffff81076455-ffffffff8107649d: __kgdb_notify.cold (STB_LOCAL)
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
