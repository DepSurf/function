# Function: <code>mem_cgroup_hierarchy_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811f9b30)
Location: mm/memcontrol.c:2781
Inline: False
```
**Symbols:**

```
ffffffff811f9b30-ffffffff811f9bd6: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121d700)
Location: mm/memcontrol.c:2714
Inline: False
```
**Symbols:**

```
ffffffff8121d700-ffffffff8121d77f: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8122fc70)
Location: mm/memcontrol.c:2687
Inline: False
```
**Symbols:**

```
ffffffff8122fc70-ffffffff8122fcef: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123b580)
Location: mm/memcontrol.c:2695
Inline: False
```
**Symbols:**

```
ffffffff8123b580-ffffffff8123b5fa: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125ae10)
Location: mm/memcontrol.c:2722
Inline: False
```
**Symbols:**

```
ffffffff8125ae10-ffffffff8125ae8a: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127eb40)
Location: mm/memcontrol.c:2653
Inline: False
```
**Symbols:**

```
ffffffff8127eb40-ffffffff8127ebba: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812932d0)
Location: mm/memcontrol.c:2927
Inline: False
```
**Symbols:**

```
ffffffff812932d0-ffffffff8129334a: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae290)
Location: mm/memcontrol.c:3162
Inline: False
```
**Symbols:**

```
ffffffff812ae290-ffffffff812ae2fb: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bfc90)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffffffff812bfc90-ffffffff812bfd02: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f4e50)
Location: mm/memcontrol.c:3254
Inline: False
```
**Symbols:**

```
ffffffff812f4e50-ffffffff812f4ec2: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81300efe)
Location: mm/memcontrol.c:3543
Inline: True
```
**Symbols:**

```
ffffffff81300ef0-ffffffff81300f16: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff81be9b9c-ffffffff81be9bb9: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8130749e)
Location: mm/memcontrol.c:3379
Inline: True
```
**Symbols:**

```
ffffffff81307490-ffffffff813074b1: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff81bdbbb8-ffffffff81bdbbd6: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81cc2764)
Location: mm/memcontrol.c:3547
Inline: True
```
**Symbols:**

```
ffffffff81351280-ffffffff813512b7: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff81cc2750-ffffffff81cc2781: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff813c9b08)
Location: mm/memcontrol.c:3540
Inline: True
```
**Symbols:**

```
ffffffff813c9af0-ffffffff813c9b4c: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff81e74d11-ffffffff81e74d25: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff8144f1c8)
Location: mm/memcontrol.c:3641
Inline: True
```
**Symbols:**

```
ffffffff8144f1b0-ffffffff8144f20c: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff8206801e-ffffffff82068032: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81484cb8)
Location: mm/memcontrol.c:3655
Inline: True
```
**Symbols:**

```
ffffffff81484ca0-ffffffff81484cfc: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff820e78f3-ffffffff820e7907: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff814b40e8)
Location: mm/memcontrol.c:3847
Inline: True
```
**Symbols:**

```
ffffffff814b40d0-ffffffff814b412c: mem_cgroup_hierarchy_write (STB_LOCAL)
ffffffff821c4607-ffffffff821c461b: mem_cgroup_hierarchy_write.cold (STB_LOCAL)
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
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010361670)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffff800010361670-ffff8000103616f0: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0553c14)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
c0553c14-c0553cb0: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044d740)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
c00000000044d740-c00000000044d810: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000240ce4)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffffffe000240ce4-ffffffe000240d48: mem_cgroup_hierarchy_write (STB_LOCAL)
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
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b8270)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffffffff812b8270-ffffffff812b82e2: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812a9440)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffffffff812a9440-ffffffff812a94b2: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6080)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffffffff812b6080-ffffffff812b60f2: mem_cgroup_hierarchy_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_hierarchy_write(struct cgroup_subsys_state *css, struct cftype *cft, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6760)
Location: mm/memcontrol.c:3371
Inline: False
```
**Symbols:**

```
ffffffff812c6760-ffffffff812c67e5: mem_cgroup_hierarchy_write (STB_LOCAL)
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
