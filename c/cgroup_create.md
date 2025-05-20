# Function: <code>cgroup_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811201ca)
Location: kernel/cgroup.c:5207
Inline: True
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
In kernel/cgroup.c (ffffffff8112868a)
Location: kernel/cgroup.c:5229
Inline: True
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
In kernel/cgroup/cgroup.c (ffffffff81127b62)
Location: kernel/cgroup/cgroup.c:4182
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
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
In kernel/cgroup/cgroup.c (ffffffff81134009)
Location: kernel/cgroup/cgroup.c:4777
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
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
In kernel/cgroup/cgroup.c (ffffffff811426f4)
Location: kernel/cgroup/cgroup.c:4817
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
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
In kernel/cgroup/cgroup.c (ffffffff8114e174)
Location: kernel/cgroup/cgroup.c:4904
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81157860)
Location: kernel/cgroup/cgroup.c:5206
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81157860-ffffffff81157b7d: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811634d0)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff811634d0-ffffffff811637ed: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174750)
Location: kernel/cgroup/cgroup.c:5178
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81174750-ffffffff81174a88: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171420)
Location: kernel/cgroup/cgroup.c:5170
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81171420-ffffffff8117174c: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172080)
Location: kernel/cgroup/cgroup.c:5154
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81172080-ffffffff81172372: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81198b70)
Location: kernel/cgroup/cgroup.c:5344
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81198b70-ffffffff81198e62: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c8d00)
Location: kernel/cgroup/cgroup.c:5355
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff811c8d00-ffffffff811c8ff8: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120bda0)
Location: kernel/cgroup/cgroup.c:5572
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff8120bda0-ffffffff8120c08d: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812213b0)
Location: kernel/cgroup/cgroup.c:5553
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff812213b0-ffffffff81221694: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent, const char *name, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81239090)
Location: kernel/cgroup/cgroup.c:5588
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81239090-ffffffff8123938a: cgroup_create (STB_LOCAL)
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
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d4cc0)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffff8000101d4cc0-ffff8000101d4fbc: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0417810)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
c0417810-c0417b30: cgroup_create (STB_LOCAL)
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
In kernel/cgroup/cgroup.c (c000000000243fd4)
Location: kernel/cgroup/cgroup.c:5221
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014e06a)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffe00014e06a-ffffffe00014e352: cgroup_create (STB_LOCAL)
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
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115baf0)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff8115baf0-ffffffff8115be0d: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ede0)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff8114ede0-ffffffff8114f0f7: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811598c0)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff811598c0-ffffffff81159bdd: cgroup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup *cgroup_create(struct cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166930)
Location: kernel/cgroup/cgroup.c:5221
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
**Symbols:**

```
ffffffff81166930-ffffffff81166c44: cgroup_create (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param added. </b>
<code>umode_t mode</code>
</li>
</ul>
</details>
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
