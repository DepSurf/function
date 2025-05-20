# Function: <code>sel_make_policy_nodes</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:506
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814042e0-ffffffff81404980: sel_make_policy_nodes (STB_LOCAL)
ffffffff81405fd4-ffffffff81405ff5: sel_make_policy_nodes.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:506
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8141ffd0-ffffffff81420686: sel_make_policy_nodes (STB_LOCAL)
ffffffff81421b23-ffffffff81421b4c: sel_make_policy_nodes.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8144dc20-ffffffff8144e28d: sel_make_policy_nodes (STB_LOCAL)
ffffffff8144f6d1-ffffffff8144f6ff: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81467a40-ffffffff814680ad: sel_make_policy_nodes (STB_LOCAL)
ffffffff81469549-ffffffff81469577: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:511
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814bc120-ffffffff814bc234: sel_make_policy_nodes (STB_LOCAL)
ffffffff814bd6fe-ffffffff814bd720: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:536
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814d9a70-ffffffff814d9cf8: sel_make_policy_nodes (STB_LOCAL)
ffffffff81bf0517-ffffffff81bf0539: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814e0f20)
Location: security/selinux/selinuxfs.c:539
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff814e0f20-ffffffff814e11b0: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81539ea0)
Location: security/selinux/selinuxfs.c:539
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81539ea0-ffffffff8153a130: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff815d1830)
Location: security/selinux/selinuxfs.c:541
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff815d1830-ffffffff815d1ad8: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167f650)
Location: security/selinux/selinuxfs.c:541
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8167f650-ffffffff8167f8f8: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b7750)
Location: security/selinux/selinuxfs.c:506
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff816b7750-ffffffff816b79f8: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi, struct selinux_policy *newpolicy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f3000)
Location: security/selinux/selinuxfs.c:504
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff816f3000-ffffffff816f32d6: sel_make_policy_nodes (STB_LOCAL)
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
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffff800010555e28)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffff800010555e28-ffff8000105564c8: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c070a478)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
c070a478-c070aaf4: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b29a0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
c0000000006b29a0-c0000000006b32d4: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003ad5dc)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffe0003ad5dc-ffffffe0003adbd2: sel_make_policy_nodes (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81460020-ffffffff8146068d: sel_make_policy_nodes (STB_LOCAL)
ffffffff81461b29-ffffffff81461b57: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81450a50-ffffffff814510bd: sel_make_policy_nodes (STB_LOCAL)
ffffffff81452559-ffffffff81452587: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8145c0c0-ffffffff8145c72d: sel_make_policy_nodes (STB_LOCAL)
ffffffff8145dbc9-ffffffff8145dbf7: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sel_make_policy_nodes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:505
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff81473860-ffffffff81473ecd: sel_make_policy_nodes (STB_LOCAL)
ffffffff81475369-ffffffff81475397: sel_make_policy_nodes.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy *newpolicy</code>
</li>
</ul>
</details>
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
