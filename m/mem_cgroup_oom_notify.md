# Function: <code>mem_cgroup_oom_notify</code>

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
In mm/memcontrol.c (ffffffff811ff65b)
Location: mm/memcontrol.c:3359
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff812233d4)
Location: mm/memcontrol.c:3365
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff812358b5)
Location: mm/memcontrol.c:3338
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff8124128f)
Location: mm/memcontrol.c:3357
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81260fcf)
Location: mm/memcontrol.c:3384
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81284fe4)
Location: mm/memcontrol.c:3315
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81298170)
Location: mm/memcontrol.c:3590
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81298170-ffffffff812981fe: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b3450)
Location: mm/memcontrol.c:3915
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812b3450-ffffffff812b34de: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c4f20)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c4f20-ffffffff812c4fae: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa9f0)
Location: mm/memcontrol.c:3988
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812fa9f0-ffffffff812faa7c: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813069a0)
Location: mm/memcontrol.c:4254
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff813069a0-ffffffff81306a2c: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130d1c0)
Location: mm/memcontrol.c:4037
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8130d1c0-ffffffff8130d24c: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81358070)
Location: mm/memcontrol.c:4204
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81358070-ffffffff813580fc: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d11c0)
Location: mm/memcontrol.c:4155
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff813d11c0-ffffffff813d124f: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814565d0)
Location: mm/memcontrol.c:4265
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff814565d0-ffffffff8145665f: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148be60)
Location: mm/memcontrol.c:4289
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8148be60-ffffffff8148beef: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bb7b0)
Location: mm/memcontrol.c:4486
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff814bb7b0-ffffffff814bb83c: mem_cgroup_oom_notify (STB_LOCAL)
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
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010367bd0)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffff800010367bd0-ffff800010367cd0: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c05591ec)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c05591ec-c055928c: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0000000004555f0)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c0000000004555f0-c00000000045570c: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000245b1e)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffe000245b1e-ffffffe000245bf0: mem_cgroup_oom_notify (STB_LOCAL)
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
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd500)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812bd500-ffffffff812bd58e: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae640)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812ae640-ffffffff812ae6ce: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb310)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812bb310-ffffffff812bb39e: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_oom_notify(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cbac0)
Location: mm/memcontrol.c:4108
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812cbac0-ffffffff812cbb45: mem_cgroup_oom_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
