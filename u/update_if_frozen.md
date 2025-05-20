# Function: <code>update_if_frozen</code>

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
In kernel/cgroup_freezer.c (ffffffff81119ee8)
Location: kernel/cgroup_freezer.c:244
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
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
In kernel/cgroup_freezer.c (ffffffff81121d45)
Location: kernel/cgroup_freezer.c:244
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
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
In kernel/cgroup_freezer.c (ffffffff8112a385)
Location: kernel/cgroup_freezer.c:244
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
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
In kernel/cgroup/freezer.c (ffffffff8112b0ab)
Location: kernel/cgroup/freezer.c:244
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81137ca0)
Location: kernel/cgroup/freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81137ca0-ffffffff81137d8d: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811465b0)
Location: kernel/cgroup/freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_read
```
**Symbols:**

```
ffffffff811465b0-ffffffff811466aa: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81152150)
Location: kernel/cgroup/freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81152150-ffffffff8115224a: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e7e0)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff8115e7e0-ffffffff8115e8dd: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a430)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff8116a430-ffffffff8116a533: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8117bf60)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff8117bf60-ffffffff8117c04f: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81178d90)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81178d90-ffffffff81178e89: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81179900)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81179900-ffffffff811799f9: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1220)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff811a1220-ffffffff811a1319: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1af0)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff811d1af0-ffffffff811d1c10: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff812157c0)
Location: kernel/cgroup/legacy_freezer.c:245
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff812157c0-ffffffff812158d5: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b0f0)
Location: kernel/cgroup/legacy_freezer.c:250
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff8122b0f0-ffffffff8122b205: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff812430b0)
Location: kernel/cgroup/legacy_freezer.c:256
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff812430b0-ffffffff812431c5: update_if_frozen (STB_LOCAL)
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
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffff8000101ddf40)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffff8000101ddf40-ffff8000101de050: update_if_frozen (STB_LOCAL)
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
In kernel/cgroup/legacy_freezer.c (c041ff2c)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (c00000000024bcf0)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
c00000000024bcf0-c00000000024be78: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffe000155662)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffe000155662-ffffffe000155748: update_if_frozen (STB_LOCAL)
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
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81162a50)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81162a50-ffffffff81162b53: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81155ca0)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81155ca0-ffffffff81155da3: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81160820)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff81160820-ffffffff81160923: update_if_frozen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_if_frozen(struct cgroup_subsys_state *css);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116db90)
Location: kernel/cgroup/legacy_freezer.c:244
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
**Symbols:**

```
ffffffff8116db90-ffffffff8116dca2: update_if_frozen (STB_LOCAL)
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
