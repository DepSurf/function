# Function: <code>check_ids</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a3340)
Location: kernel/bpf/verifier.c:3482
Inline: True
```
**Symbols:**

```
ffffffff811a3340-ffffffff811a337d: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6ea0)
Location: kernel/bpf/verifier.c:4311
Inline: True
```
**Symbols:**

```
ffffffff811b6ea0-ffffffff811b6edd: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5fb0)
Location: kernel/bpf/verifier.c:5293
Inline: True
```
**Symbols:**

```
ffffffff811c5fb0-ffffffff811c5fed: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7b20)
Location: kernel/bpf/verifier.c:6695
Inline: True
```
**Symbols:**

```
ffffffff811d7b20-ffffffff811d7b5f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4210)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffffffff811e4210-ffffffff811e424f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202ee0)
Location: kernel/bpf/verifier.c:7843
Inline: True
```
**Symbols:**

```
ffffffff81202ee0-ffffffff81202f1f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202c10)
Location: kernel/bpf/verifier.c:8631
Inline: True
```
**Symbols:**

```
ffffffff81202c10-ffffffff81202c4f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct bpf_id_pair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203870)
Location: kernel/bpf/verifier.c:9802
Inline: True
```
**Symbols:**

```
ffffffff81203870-ffffffff812038af: check_ids (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81236fc9)
Location: kernel/bpf/verifier.c:10133
Inline: True
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
In kernel/bpf/verifier.c (ffffffff8127b5a6)
Location: kernel/bpf/verifier.c:11190
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
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
In kernel/bpf/verifier.c (ffffffff812d39a5)
Location: kernel/bpf/verifier.c:13162
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:func_states_equal
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct bpf_idmap *idmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f6540)
Location: kernel/bpf/verifier.c:15141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:stacksafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regs_exact
  - kernel/bpf/verifier.c:regs_exact
```
**Symbols:**

```
ffffffff812f6540-ffffffff812f65e2: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct bpf_idmap *idmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81314e20)
Location: kernel/bpf/verifier.c:16186
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:stacksafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regs_exact
  - kernel/bpf/verifier.c:regs_exact
```
**Symbols:**

```
ffffffff81314e20-ffffffff81314ec2: check_ids (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010267328)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffff800010267328-ffff8000102673c0: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0499718)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
c0499718-c04997bc: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030c970)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
c00000000030c970-c00000000030c9ec: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a2708)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffffffe0001a2708-ffffffe0001a277e: check_ids (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dc830)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffffffff811dc830-ffffffff811dc86f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf5f0)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffffffff811cf5f0-ffffffff811cf62f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da600)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffffffff811da600-ffffffff811da63f: check_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool check_ids(u32 old_id, u32 cur_id, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8a10)
Location: kernel/bpf/verifier.c:6710
Inline: True
```
**Symbols:**

```
ffffffff811e8a10-ffffffff811e8a4f: check_ids (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct idpair *idmap</code> ➡️ <code>struct bpf_id_pair *idmap</code>
</li>
</ul>
</details>
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
