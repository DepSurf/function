# Function: <code>css_from_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811199e0)
Location: kernel/cgroup.c:5950
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff811199e0-ffffffff81119a24: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811216d0)
Location: kernel/cgroup.c:6190
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff811216d0-ffffffff8112170b: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129c50)
Location: kernel/cgroup.c:6219
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81129c50-ffffffff81129c8c: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128a30)
Location: kernel/cgroup/cgroup.c:5039
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81128a30-ffffffff81128a4d: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81135080)
Location: kernel/cgroup/cgroup.c:5706
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81135080-ffffffff8113509d: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811437c0)
Location: kernel/cgroup/cgroup.c:5744
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff811437c0-ffffffff811437dd: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f2e0)
Location: kernel/cgroup/cgroup.c:5847
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8114f2e0-ffffffff8114f2fd: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115afe0)
Location: kernel/cgroup/cgroup.c:6224
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8115afe0-ffffffff8115affd: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166c90)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81166c90-ffffffff81166cad: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811783a0)
Location: kernel/cgroup/cgroup.c:6309
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff811783a0-ffffffff811783bd: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811750e0)
Location: kernel/cgroup/cgroup.c:6301
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff811750e0-ffffffff811750fd: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175c20)
Location: kernel/cgroup/cgroup.c:6279
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81175c20-ffffffff81175c3d: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d210)
Location: kernel/cgroup/cgroup.c:6525
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8119d210-ffffffff8119d22d: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd540)
Location: kernel/cgroup/cgroup.c:6555
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff811cd540-ffffffff811cd565: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210b40)
Location: kernel/cgroup/cgroup.c:6801
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81210b40-ffffffff81210b65: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81226480)
Location: kernel/cgroup/cgroup.c:6784
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81226480-ffffffff812264a5: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e110)
Location: kernel/cgroup/cgroup.c:6825
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8123e110-ffffffff8123e135: css_from_id (STB_GLOBAL)
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
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8ab0)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffff8000101d8ab0-ffff8000101d8ae4: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041b724)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
c041b724-c041b74c: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000245de0)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
c000000000245de0-c000000000245e20: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151a86)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffe000151a86-ffffffe000151aba: css_from_id (STB_GLOBAL)
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
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f2b0)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8115f2b0-ffffffff8115f2cd: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81152540)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff81152540-ffffffff8115255d: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d080)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8115d080-ffffffff8115d09d: css_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_subsys_state *css_from_id(int id, struct cgroup_subsys *ss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a1d0)
Location: kernel/cgroup/cgroup.c:6239
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:inode_switch_wbs
```
**Symbols:**

```
ffffffff8116a1d0-ffffffff8116a1ed: css_from_id (STB_GLOBAL)
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
