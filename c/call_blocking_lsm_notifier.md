# Function: <code>call_blocking_lsm_notifier</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c0c0)
Location: security/security.c:461
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8143c0c0-ffffffff8143c0dc: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455d70)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81455d70-ffffffff81455d8c: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8840)
Location: security/security.c:548
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814a8840-ffffffff814a885c: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5db0)
Location: security/security.c:550
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814c5db0-ffffffff814c5dcc: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc070)
Location: security/security.c:553
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814cc070-ffffffff814cc08c: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525040)
Location: security/security.c:553
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81525040-ffffffff8152505c: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8ff0)
Location: security/security.c:581
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff815b8ff0-ffffffff815b9016: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664710)
Location: security/security.c:630
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff81664710-ffffffff81664736: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169cbf0)
Location: security/security.c:638
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8169cbf0-ffffffff8169cc16: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9540)
Location: security/security.c:643
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff816d9540-ffffffff816d9566: call_blocking_lsm_notifier (STB_GLOBAL)
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
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105413e8)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffff8000105413e8-ffff800010541424: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7428)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
c06f7428-c06f7454: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693b50)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
c000000000693b50-c000000000693b98: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e12e)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffe00039e12e-ffffffe00039e16c: call_blocking_lsm_notifier (STB_GLOBAL)
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
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e350)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8144e350-ffffffff8144e36c: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eda0)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8143eda0-ffffffff8143edbc: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a3f0)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff8144a3f0-ffffffff8144a40c: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int call_blocking_lsm_notifier(enum lsm_event event, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814617c0)
Location: security/security.c:495
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_enforce
```
**Symbols:**

```
ffffffff814617c0-ffffffff814617dc: call_blocking_lsm_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
