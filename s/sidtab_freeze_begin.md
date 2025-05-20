# Function: <code>sidtab_freeze_begin</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sidtab_freeze_begin(struct sidtab *s, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814e5080)
Location: security/selinux/ss/sidtab.c:487
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff814e5080-ffffffff814e50b0: sidtab_freeze_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sidtab_freeze_begin(struct sidtab *s, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8153e730)
Location: security/selinux/ss/sidtab.c:487
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff8153e730-ffffffff8153e760: sidtab_freeze_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sidtab_freeze_begin(struct sidtab *s, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff815d6120)
Location: security/selinux/ss/sidtab.c:487
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff815d6120-ffffffff815d615a: sidtab_freeze_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sidtab_freeze_begin(struct sidtab *s, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816843d0)
Location: security/selinux/ss/sidtab.c:492
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff816843d0-ffffffff8168440a: sidtab_freeze_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sidtab_freeze_begin(struct sidtab *s, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816bc740)
Location: security/selinux/ss/sidtab.c:492
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff816bc740-ffffffff816bc77a: sidtab_freeze_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sidtab_freeze_begin(struct sidtab *s, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816f9270)
Location: security/selinux/ss/sidtab.c:492
Inline: False
Direct callers:
  - security/selinux/ss/services.c:selinux_policy_commit
```
**Symbols:**

```
ffffffff816f9270-ffffffff816f92aa: sidtab_freeze_begin (STB_GLOBAL)
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
