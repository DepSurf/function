# Function: <code>out_of_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190fe0)
Location: mm/oom_kill.c:673
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81190fe0-ffffffff81191436: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a57f0)
Location: mm/oom_kill.c:989
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff811a57f0-ffffffff811a5bf2: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b5b00)
Location: mm/oom_kill.c:984
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff811b5b00-ffffffff811b5fb5: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd850)
Location: mm/oom_kill.c:994
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff811bd850-ffffffff811bdd11: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d2490)
Location: mm/oom_kill.c:1019
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff811d2490-ffffffff811d2976: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1021
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff811f3fba-ffffffff811f3fff: out_of_memory.cold.29 (STB_LOCAL)
ffffffff811f33d0-ffffffff811f387c: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81205444)
Location: mm/oom_kill.c:1074
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81205f54-ffffffff81205fd2: out_of_memory.cold.32 (STB_LOCAL)
ffffffff812053d0-ffffffff81205842: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff8121ceb0)
Location: mm/oom_kill.c:1042
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff8121c3d0-ffffffff8121c79b: out_of_memory.part.0 (STB_LOCAL)
ffffffff8121d1fb-ffffffff8121d27e: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff8121ceb0-ffffffff8121cf6c: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff8122a890)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81229da0-ffffffff8122a16b: out_of_memory.part.0 (STB_LOCAL)
ffffffff8122abd8-ffffffff8122ac5b: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff8122a890-ffffffff8122a954: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff812576a0)
Location: mm/oom_kill.c:1045
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81256cc0-ffffffff81256efd: out_of_memory.part.0 (STB_LOCAL)
ffffffff81257996-ffffffff81257a19: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff812576a0-ffffffff8125771b: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81262280)
Location: mm/oom_kill.c:1049
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81261860-ffffffff81261ad8: out_of_memory.part.0 (STB_LOCAL)
ffffffff81be6d09-ffffffff81be6d8c: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff81262280-ffffffff812622fb: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81266d10)
Location: mm/oom_kill.c:1048
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff812663f0-ffffffff8126665a: out_of_memory.part.0 (STB_LOCAL)
ffffffff81bd8aa2-ffffffff81bd8b25: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff81266d10-ffffffff81266d8b: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1049
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81cba468-ffffffff81cba4ff: out_of_memory.cold (STB_LOCAL)
ffffffff812a3510-ffffffff812a37e9: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1107
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81e6bb8e-ffffffff81e6bc21: out_of_memory.cold (STB_LOCAL)
ffffffff812fb430-ffffffff812fb71f: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1106
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_age_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff82062448-ffffffff8206245d: out_of_memory.cold (STB_LOCAL)
ffffffff813654b0-ffffffff8136581c: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1106
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_age_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff820e1c23-ffffffff820e1c38: out_of_memory.cold (STB_LOCAL)
ffffffff81397970-ffffffff81397cbf: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1104
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_age_node
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff821be648-ffffffff821be65d: out_of_memory.cold (STB_LOCAL)
ffffffff813c17a0-ffffffff813c1aeb: out_of_memory (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffff8000102b7cd8)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffff8000102b7cd8-ffff8000102b80ec: out_of_memory.part.0 (STB_LOCAL)
ffff8000102b89f8-ffff8000102b8ad8: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e517c)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
c04e517c-c04e54bc: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (c00000000036fb70)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
c00000000036fb70-c00000000037017c: out_of_memory.part.0 (STB_LOCAL)
c000000000370c60-c000000000370dd0: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dc68e)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffe0001dc68e-ffffffe0001dc930: out_of_memory (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81222ee0)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff812223f0-ffffffff812227bb: out_of_memory.part.0 (STB_LOCAL)
ffffffff81223228-ffffffff812232ab: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff81222ee0-ffffffff81222fa4: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81216090)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff812155a0-ffffffff8121596b: out_of_memory.part.0 (STB_LOCAL)
ffffffff812163d8-ffffffff8121645b: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff81216090-ffffffff81216154: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81220c80)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff81220190-ffffffff8122055b: out_of_memory.part.0 (STB_LOCAL)
ffffffff81220fc8-ffffffff8122104b: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff81220c80-ffffffff81220d44: out_of_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool out_of_memory(struct oom_control *oc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff8122fe20)
Location: mm/oom_kill.c:1043
Inline: True
Direct callers:
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/tty/sysrq.c:moom_callback
```
**Symbols:**

```
ffffffff8122f2b0-ffffffff8122f685: out_of_memory.part.0 (STB_LOCAL)
ffffffff8123017d-ffffffff81230200: out_of_memory.part.0.cold (STB_LOCAL)
ffffffff8122fe20-ffffffff8122fee4: out_of_memory (STB_GLOBAL)
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
