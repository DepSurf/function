# Function: <code>btf_verifier_log_vsi</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811eec10)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff811eec10-ffffffff811eed1e: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fb350)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff811fb350-ffffffff811fb45e: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81221a70)
Location: kernel/bpf/btf.c:794
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff81221a70-ffffffff81221bb6: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224cd0)
Location: kernel/bpf/btf.c:1379
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff81224cd0-ffffffff81224e1d: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229810)
Location: kernel/bpf/btf.c:1380
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff81229810-ffffffff8122995d: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81261c10)
Location: kernel/bpf/btf.c:1380
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff81261c10-ffffffff81261d5d: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ad580)
Location: kernel/bpf/btf.c:1475
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff812ad580-ffffffff812ad6dd: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130cbe0)
Location: kernel/bpf/btf.c:1478
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff8130cbe0-ffffffff8130cd3d: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133c2b0)
Location: kernel/bpf/btf.c:1510
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff8133c2b0-ffffffff8133c3f2: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81362470)
Location: kernel/bpf/btf.c:1511
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff81362470-ffffffff813625b2: btf_verifier_log_vsi (STB_LOCAL)
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
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff8000102815e8)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffff8000102815e8-ffff800010281724: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b2a1c)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
c04b2a1c-c04b2b34: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032ba60)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
c00000000032ba60-c00000000032bb88: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b7a14)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffe0001b7a14-ffffffe0001b7ae8: btf_verifier_log_vsi (STB_LOCAL)
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
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3970)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff811f3970-ffffffff811f3a7e: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e66c0)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff811e66c0-ffffffff811e67ce: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1740)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff811f1740-ffffffff811f184e: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void btf_verifier_log_vsi(struct btf_verifier_env *env, const struct btf_type *datasec_type, const struct btf_var_secinfo *vsi, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ffc50)
Location: kernel/bpf/btf.c:770
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
**Symbols:**

```
ffffffff811ffc50-ffffffff811ffd5e: btf_verifier_log_vsi (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
