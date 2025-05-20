# Function: <code>convert_ctx_accesses</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81176060)
Location: kernel/bpf/verifier.c:2093
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81176060-ffffffff811762fa: convert_ctx_accesses.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81184be0)
Location: kernel/bpf/verifier.c:2603
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81184be0-ffffffff81184d1b: convert_ctx_accesses.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e470)
Location: kernel/bpf/verifier.c:3057
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8118e470-ffffffff8118e63c: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81194760)
Location: kernel/bpf/verifier.c:3529
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81194760-ffffffff81194a9f: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a2c10)
Location: kernel/bpf/verifier.c:4356
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811a2c10-ffffffff811a2f5d: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811bdf80)
Location: kernel/bpf/verifier.c:5280
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811bdf80-ffffffff811be381: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cc4c0)
Location: kernel/bpf/verifier.c:6468
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811cc4c0-ffffffff811cc9dd: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8486
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811ded20-ffffffff811df22d: convert_ctx_accesses (STB_LOCAL)
ffffffff811e555d-ffffffff811e55ae: convert_ctx_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb4e0)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811eb4e0-ffffffff811eb9ff: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120a610)
Location: kernel/bpf/verifier.c:9615
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8120a610-ffffffff8120ab52: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c7c0)
Location: kernel/bpf/verifier.c:10545
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8120c7c0-ffffffff8120cd3f: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e1d0)
Location: kernel/bpf/verifier.c:11828
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8120e1d0-ffffffff8120e80b: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12211
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812428b0-ffffffff8124302f: convert_ctx_accesses (STB_LOCAL)
ffffffff81cb870e-ffffffff81cb886d: convert_ctx_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13270
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81287fc0-ffffffff81288851: convert_ctx_accesses (STB_LOCAL)
ffffffff81e6999a-ffffffff81e69b07: convert_ctx_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:15251
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812de8b0-ffffffff812df122: convert_ctx_accesses (STB_LOCAL)
ffffffff820605d8-ffffffff82060749: convert_ctx_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:17468
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812fd6e0-ffffffff812fdefd: convert_ctx_accesses (STB_LOCAL)
ffffffff820ded46-ffffffff820dee9c: convert_ctx_accesses.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:18622
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8131cbf0-ffffffff8131d51d: convert_ctx_accesses (STB_LOCAL)
ffffffff821baddc-ffffffff821baf3e: convert_ctx_accesses.cold (STB_LOCAL)
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
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026ee30)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffff80001026ee30-ffff80001026f328: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a11e8)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c04a11e8-c04a170c: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000315790)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c000000000315790-c000000000315f78: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a8962)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffe0001a8962-ffffffe0001a8d0c: convert_ctx_accesses (STB_LOCAL)
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
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3b00)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e3b00-ffffffff811e401f: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d68c0)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811d68c0-ffffffff811d6ddf: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e18d0)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e18d0-ffffffff811e1def: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int convert_ctx_accesses(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811efce0)
Location: kernel/bpf/verifier.c:8501
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811efce0-ffffffff811f01ff: convert_ctx_accesses (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
