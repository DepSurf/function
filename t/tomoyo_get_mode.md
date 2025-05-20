# Function: <code>tomoyo_get_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff81373da0)
Location: security/tomoyo/util.c:975
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81373da0-ffffffff81373de7: tomoyo_get_mode.part.4 (STB_LOCAL)
ffffffff81374770-ffffffff81374793: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aabde)
Location: security/tomoyo/util.c:975
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff813aa1a0-ffffffff813aa1e7: tomoyo_get_mode.part.4 (STB_LOCAL)
ffffffff813aab70-ffffffff813aab93: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c175e)
Location: security/tomoyo/util.c:975
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff813c0d20-ffffffff813c0d67: tomoyo_get_mode.part.4 (STB_LOCAL)
ffffffff813c16f0-ffffffff813c1713: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d80ee)
Location: security/tomoyo/util.c:977
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff813d76c0-ffffffff813d7707: tomoyo_get_mode.part.5 (STB_LOCAL)
ffffffff813d8080-ffffffff813d80a3: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fe53e)
Location: security/tomoyo/util.c:957
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff813fdc10-ffffffff813fdc57: tomoyo_get_mode.part.5 (STB_LOCAL)
ffffffff813fe4d0-ffffffff813fe4f3: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142f450)
Location: security/tomoyo/util.c:957
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8142e4e0-ffffffff8142e527: tomoyo_get_mode.part.5 (STB_LOCAL)
ffffffff8142f3d0-ffffffff8142f3f3: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144be70)
Location: security/tomoyo/util.c:957
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8144aeb0-ffffffff8144aef7: tomoyo_get_mode.part.6 (STB_LOCAL)
ffffffff8144bdf0-ffffffff8144be13: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff81479bd4)
Location: security/tomoyo/util.c:969
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81479260-ffffffff814792a4: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffff81479b50-ffffffff81479b73: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff814938d4)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81492f60-ffffffff81492fa4: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffff81493850-ffffffff81493873: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814eacd6)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
```
**Symbols:**

```
ffffffff814eac20-ffffffff814eac77: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff815080d6)
Location: security/tomoyo/util.c:992
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
```
**Symbols:**

```
ffffffff81508020-ffffffff81508077: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150ec5b)
Location: security/tomoyo/util.c:992
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
```
**Symbols:**

```
ffffffff8150eba0-ffffffff8150ebf7: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8156c774)
Location: security/tomoyo/util.c:992
Inline: True
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81cd6207-ffffffff81cd6221: tomoyo_get_mode.cold (STB_LOCAL)
ffffffff8156c730-ffffffff8156c810: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff81608b3e)
Location: security/tomoyo/util.c:992
Inline: True
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff81e88ff4-ffffffff81e8900e: tomoyo_get_mode.cold (STB_LOCAL)
ffffffff81608af0-ffffffff81608be4: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff816ba41e)
Location: security/tomoyo/util.c:992
Inline: True
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff82074a85-ffffffff82074a9f: tomoyo_get_mode.cold (STB_LOCAL)
ffffffff816ba3d0-ffffffff816ba4c4: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff816f2db5)
Location: security/tomoyo/util.c:992
Inline: True
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff820f45dc-ffffffff820f45f1: tomoyo_get_mode.cold (STB_LOCAL)
ffffffff816f2d70-ffffffff816f2e5f: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8172fb75)
Location: security/tomoyo/util.c:992
Inline: True
Direct callers:
  - security/tomoyo/domain.c:tomoyo_environ
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff821d1a21-ffffffff821d1a36: tomoyo_get_mode.cold (STB_LOCAL)
ffffffff8172fb30-ffffffff8172fc1f: tomoyo_get_mode (STB_GLOBAL)
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
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffff800010588cf4)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffff800010587fd0-ffff800010588058: tomoyo_get_mode.part.0 (STB_LOCAL)
ffff800010588c38-ffff800010588c9c: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (c073a0bc)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
c07395b4-c0739604: tomoyo_get_mode.part.0 (STB_LOCAL)
c073a02c-c073a064: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (c0000000006f97c8)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
c0000000006f8480-c0000000006f8518: tomoyo_get_mode.part.0 (STB_LOCAL)
c0000000006f9720-c0000000006f9754: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d7be8)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffe0003d714e-ffffffe0003d71d0: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffe0003d7b68-ffffffe0003d7bae: tomoyo_get_mode (STB_GLOBAL)
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
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148beb4)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8148b540-ffffffff8148b584: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffff8148be30-ffffffff8148be53: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c8d4)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8147bf60-ffffffff8147bfa4: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffff8147c850-ffffffff8147c873: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff81487f54)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff814875e0-ffffffff81487624: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffff81487ed0-ffffffff81487ef3: tomoyo_get_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tomoyo_get_mode(const struct tomoyo_policy_namespace *ns, const u8 profile, const u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149fa94)
Location: security/tomoyo/util.c:970
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_init_request_info
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/file.c:tomoyo_execute_permission
  - security/tomoyo/util.c:tomoyo_init_request_info
```
**Symbols:**

```
ffffffff8149f120-ffffffff8149f164: tomoyo_get_mode.part.0 (STB_LOCAL)
ffffffff8149fa10-ffffffff8149fa33: tomoyo_get_mode (STB_GLOBAL)
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
