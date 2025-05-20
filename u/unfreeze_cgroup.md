# Function: <code>unfreeze_cgroup</code>

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
In kernel/cgroup_freezer.c (ffffffff81119d42)
Location: kernel/cgroup_freezer.c:329
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
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
In kernel/cgroup_freezer.c (ffffffff81121b52)
Location: kernel/cgroup_freezer.c:329
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
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
In kernel/cgroup_freezer.c (ffffffff8112a192)
Location: kernel/cgroup_freezer.c:329
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
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
In kernel/cgroup/freezer.c (ffffffff8112ae47)
Location: kernel/cgroup/freezer.c:329
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81137bd0)
Location: kernel/cgroup/freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81137bd0-ffffffff81137c2e: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811464e0)
Location: kernel/cgroup/freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811464e0-ffffffff8114653e: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81152080)
Location: kernel/cgroup/freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81152080-ffffffff811520de: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e710)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8115e710-ffffffff8115e76e: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a350)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8116a350-ffffffff8116a3ba: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8117be90)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8117be90-ffffffff8117beee: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81178cc0)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81178cc0-ffffffff81178d1e: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81179830)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81179830-ffffffff8117988e: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811a1150)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811a1150-ffffffff811a11ae: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811d19c0)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811d19c0-ffffffff811d1a46: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81215630)
Location: kernel/cgroup/legacy_freezer.c:322
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81215630-ffffffff812156b6: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8122af60)
Location: kernel/cgroup/legacy_freezer.c:327
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8122af60-ffffffff8122afe6: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81242f20)
Location: kernel/cgroup/legacy_freezer.c:333
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81242f20-ffffffff81242fa6: unfreeze_cgroup (STB_LOCAL)
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
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffff8000101ddec8)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
```
**Symbols:**

```
ffff8000101ddec8-ffff8000101ddf40: unfreeze_cgroup (STB_LOCAL)
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
In kernel/cgroup/legacy_freezer.c (c041fcc8)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (c00000000024bc50)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
```
**Symbols:**

```
c00000000024bc50-c00000000024bce4: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffe00015560e)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
```
**Symbols:**

```
ffffffe00015560e-ffffffe000155662: unfreeze_cgroup (STB_LOCAL)
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
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81162970)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81162970-ffffffff811629da: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81155bc0)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81155bc0-ffffffff81155c2a: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81160740)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81160740-ffffffff811607aa: unfreeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unfreeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116dab0)
Location: kernel/cgroup/legacy_freezer.c:329
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8116dab0-ffffffff8116db1a: unfreeze_cgroup (STB_LOCAL)
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
