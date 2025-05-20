# Function: <code>may_update_sockmap</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120aa20)
Location: kernel/bpf/verifier.c:4341
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff8120aa20-ffffffff8120aa85: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120ca60)
Location: kernel/bpf/verifier.c:5091
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff8120ca60-ffffffff8120cac5: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81240c80)
Location: kernel/bpf/verifier.c:5288
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff81240c80-ffffffff81240ce5: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812861c0)
Location: kernel/bpf/verifier.c:6120
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff812861c0-ffffffff81286247: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812dd2e0)
Location: kernel/bpf/verifier.c:6855
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff812dd2e0-ffffffff812dd367: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f6c30)
Location: kernel/bpf/verifier.c:8217
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff812f6c30-ffffffff812f6cb7: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool may_update_sockmap(struct bpf_verifier_env *env, int func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81315bb0)
Location: kernel/bpf/verifier.c:8734
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_func_compatibility
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff81315bb0-ffffffff81315c37: may_update_sockmap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
