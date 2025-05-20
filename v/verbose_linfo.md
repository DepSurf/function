# Function: <code>verbose_linfo</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cd1f0)
Location: kernel/bpf/verifier.c:299
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
```
**Symbols:**

```
ffffffff811cd1f0-ffffffff811cd35b: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dff80)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811dff80-ffffffff811e00f9: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ec740)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811ec740-ffffffff811ec8b9: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120ed20)
Location: kernel/bpf/verifier.c:355
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffffffff8120ed20-ffffffff8120ee99: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120f920)
Location: kernel/bpf/verifier.c:359
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffffffff8120f920-ffffffff8120fa9d: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812112a0)
Location: kernel/bpf/verifier.c:378
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812112a0-ffffffff8121141d: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81246470)
Location: kernel/bpf/verifier.c:379
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff81246470-ffffffff812465ed: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128c4d0)
Location: kernel/bpf/verifier.c:382
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff8128c4d0-ffffffff8128c673: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e4a00)
Location: kernel/bpf/verifier.c:384
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812e4a00-ffffffff812e4ba3: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fc040)
Location: kernel/bpf/verifier.c:380
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff812fc040-ffffffff812fc1b5: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff813457f0)
Location: kernel/bpf/log.c:360
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
**Symbols:**

```
ffffffff813457f0-ffffffff81345971: verbose_linfo (STB_GLOBAL)
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
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010270018)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffff800010270018-ffff8000102701ac: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a22f8)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
c04a22f8-c04a245c: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000316f20)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
c000000000316f20-c0000000003170c8: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a97d8)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_write
```
**Symbols:**

```
ffffffe0001a97d8-ffffffe0001a98ea: verbose_linfo (STB_LOCAL)
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
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4d60)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e4d60-ffffffff811e4ed9: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7b20)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d7b20-ffffffff811d7c99: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2b30)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e2b30-ffffffff811e2ca9: verbose_linfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env *env, u32 insn_off, const char *prefix_fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f0f00)
Location: kernel/bpf/verifier.c:291
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:push_insn
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811f0f00-ffffffff811f1079: verbose_linfo (STB_LOCAL)
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
