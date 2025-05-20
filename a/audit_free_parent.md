# Function: <code>audit_free_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811299e0)
Location: kernel/audit_watch.c:69
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_free_mark
  - kernel/audit_watch.c:audit_add_watch
```
**Symbols:**

```
ffffffff811299e0-ffffffff81129a19: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81131b90)
Location: kernel/audit_watch.c:70
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81131b90-ffffffff81131bcc: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113b900)
Location: kernel/audit_watch.c:70
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff8113b900-ffffffff8113b93c: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113cfc0)
Location: kernel/audit_watch.c:71
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff8113cfc0-ffffffff8113cfe1: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81149d80)
Location: kernel/audit_watch.c:71
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81149d80-ffffffff81149da1: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81158790)
Location: kernel/audit_watch.c:71
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81158790-ffffffff811587ac: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81165780)
Location: kernel/audit_watch.c:71
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81165780-ffffffff8116579c: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit_watch.c (0)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff811722e0-ffffffff81172306: audit_free_parent (STB_LOCAL)
ffffffff81172ffc-ffffffff8117300f: audit_free_parent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117e190)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff8117e190-ffffffff8117e1b1: audit_free_parent (STB_LOCAL)
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
In kernel/audit_watch.c (ffffffff811921d0)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
In kernel/audit_watch.c (ffffffff8118f360)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
In kernel/audit_watch.c (ffffffff811902ae)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
In kernel/audit_watch.c (ffffffff811b918e)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
In kernel/audit_watch.c (ffffffff811ec1c5)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
In kernel/audit_watch.c (ffffffff81232625)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
In kernel/audit_watch.c (ffffffff812492ab)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81263164)
Location: kernel/audit_watch.c:58
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
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
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffff8000101f2fd8)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffff8000101f2fd8-ffff8000101f3028: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0433508)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
c0433508-c0433554: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0000000002679a0)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
c0000000002679a0-c0000000002679e8: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffe000166542)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffe000166542-ffffffe000166588: audit_free_parent (STB_LOCAL)
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
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811767b0)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff811767b0-ffffffff811767d1: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81169950)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81169950-ffffffff81169971: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81174580)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81174580-ffffffff811745a1: audit_free_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_free_parent(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81181e60)
Location: kernel/audit_watch.c:58
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_watch_free_mark
```
**Symbols:**

```
ffffffff81181e60-ffffffff81181e81: audit_free_parent (STB_LOCAL)
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
