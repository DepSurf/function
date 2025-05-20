# Function: <code>check_map_prog_compatibility</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81192623)
Location: kernel/bpf/verifier.c:2916
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811993ce)
Location: kernel/bpf/verifier.c:3344
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811a834a)
Location: kernel/bpf/verifier.c:4147
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811bebd4)
Location: kernel/bpf/verifier.c:5034
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811cf897)
Location: kernel/bpf/verifier.c:6199
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d94a6)
Location: kernel/bpf/verifier.c:7843
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5ba6)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812053b0)
Location: kernel/bpf/verifier.c:8968
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff812053b0-ffffffff81205530: check_map_prog_compatibility (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206000)
Location: kernel/bpf/verifier.c:9845
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81206000-ffffffff8120625f: check_map_prog_compatibility (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207f40)
Location: kernel/bpf/verifier.c:11089
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81207f40-ffffffff812081d6: check_map_prog_compatibility (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11436
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff8123b800-ffffffff8123ba98: check_map_prog_compatibility (STB_LOCAL)
ffffffff81cb7ee7-ffffffff81cb7f3a: check_map_prog_compatibility.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12492
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81281330-ffffffff81281595: check_map_prog_compatibility (STB_LOCAL)
ffffffff81e69375-ffffffff81e693c9: check_map_prog_compatibility.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:14495
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff812d90b0-ffffffff812d92f4: check_map_prog_compatibility (STB_LOCAL)
ffffffff8206013a-ffffffff82060199: check_map_prog_compatibility.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:16711
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81303050-ffffffff8130327f: check_map_prog_compatibility (STB_LOCAL)
ffffffff820df334-ffffffff820df393: check_map_prog_compatibility.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_map_prog_compatibility(struct bpf_verifier_env *env, struct bpf_map *map, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:17867
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81322b60-ffffffff81322d42: check_map_prog_compatibility (STB_LOCAL)
ffffffff821bb41e-ffffffff821bb447: check_map_prog_compatibility.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010268f04)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
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
In kernel/bpf/verifier.c (c049b200)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
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
In kernel/bpf/verifier.c (c00000000030eb48)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a3e2c)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811de1c6)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d0f86)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dbf96)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ea3a6)
Location: kernel/bpf/verifier.c:7858
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
