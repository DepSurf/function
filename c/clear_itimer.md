# Function: <code>clear_itimer</code>

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
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81155800)
Location: kernel/time/itimer.c:257
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81155800-ffffffff8115587f: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81151a60)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81151a60-ffffffff81151adf: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81152ef0)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81152ef0-ffffffff81152f75: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811774f0)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811774f0-ffffffff81177575: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ac570)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811ac570-ffffffff811ac601: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ec8e0)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff811ec8e0-ffffffff811ec971: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81201010)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff81201010-ffffffff812010a1: clear_itimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_itimer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff812174b0)
Location: kernel/time/itimer.c:253
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
**Symbols:**

```
ffffffff812174b0-ffffffff81217541: clear_itimer (STB_GLOBAL)
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
