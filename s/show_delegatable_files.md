# Function: <code>show_delegatable_files</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112d150)
Location: kernel/cgroup/cgroup.c:5878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff8112d150-ffffffff8112d1f2: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113bdd0)
Location: kernel/cgroup/cgroup.c:5916
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff8113bdd0-ffffffff8113be72: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81147650)
Location: kernel/cgroup/cgroup.c:6019
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81147650-ffffffff811476f2: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:6443
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff811528f0-ffffffff81152984: show_delegatable_files (STB_LOCAL)
ffffffff8115b3ec-ffffffff8115b3ff: show_delegatable_files.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e540)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff8115e540-ffffffff8115e5d2: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e8e0)
Location: kernel/cgroup/cgroup.c:6534
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff8116e8e0-ffffffff8116e972: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116b2e0)
Location: kernel/cgroup/cgroup.c:6526
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff8116b2e0-ffffffff8116b372: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116be60)
Location: kernel/cgroup/cgroup.c:6504
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff8116be60-ffffffff8116bef2: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81191a40)
Location: kernel/cgroup/cgroup.c:6727
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81191a40-ffffffff81191ae0: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c13d0)
Location: kernel/cgroup/cgroup.c:6723
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff811c13d0-ffffffff811c147c: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81203a60)
Location: kernel/cgroup/cgroup.c:6990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81203a60-ffffffff81203afe: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81218fc0)
Location: kernel/cgroup/cgroup.c:6971
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81218fc0-ffffffff8121905e: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81230b80)
Location: kernel/cgroup/cgroup.c:7012
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81230b80-ffffffff81230c1e: show_delegatable_files (STB_LOCAL)
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
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ced70)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffff8000101ced70-ffff8000101cee4c: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0412234)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
c0412234-c04122f8: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000238da0)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
c000000000238da0-c000000000238ed0: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000149592)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffe000149592-ffffffe000149630: show_delegatable_files (STB_LOCAL)
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
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156b60)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81156b60-ffffffff81156bf2: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149e80)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81149e80-ffffffff81149f12: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154930)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81154930-ffffffff811549c2: show_delegatable_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t show_delegatable_files(struct cftype *files, char *buf, ssize_t size, const char *prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161830)
Location: kernel/cgroup/cgroup.c:6462
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:delegate_show
  - kernel/cgroup/cgroup.c:delegate_show
```
**Symbols:**

```
ffffffff81161830-ffffffff811618c2: show_delegatable_files (STB_LOCAL)
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
