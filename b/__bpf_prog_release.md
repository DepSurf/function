# Function: <code>__bpf_prog_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731c70)
Location: net/core/filter.c:869
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:bpf_prog_destroy
  - net/core/filter.c:sk_attach_filter
```
**Symbols:**

```
ffffffff81731c70-ffffffff81731cb7: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d080)
Location: net/core/filter.c:893
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff8179d080-ffffffff8179d0c7: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cab30)
Location: net/core/filter.c:895
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff817cab30-ffffffff817cab77: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9cb0)
Location: net/core/filter.c:913
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff817e9cb0-ffffffff817e9cf7: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865320)
Location: net/core/filter.c:932
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff81865320-ffffffff81865367: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2ec0)
Location: net/core/filter.c:1141
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff818b2ec0-ffffffff818b2f07: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d7da0)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff818d7da0-ffffffff818d7de7: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81925840)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff81925840-ffffffff81925889: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81957c70)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff81957c70-ffffffff81957cb9: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a3263d)
Location: net/core/filter.c:1132
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a3497d)
Location: net/core/filter.c:1162
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1b9ed)
Location: net/core/filter.c:1162
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81acf0cd)
Location: net/core/filter.c:1163
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81c4c7cc)
Location: net/core/filter.c:1164
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81e015bc)
Location: net/core/filter.c:1166
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e7307c)
Location: net/core/filter.c:1166
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f327fc)
Location: net/core/filter.c:1171
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
  - net/core/filter.c:sk_filter_release_rcu
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
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf92a8)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffff800010bf92a8-ffff800010bf930c: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d12ed4)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
c0d12ed4-c0d12f28: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce0650)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
c000000000ce0650-c000000000ce06e8: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077b296)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffe00077b296-ffffffe00077b300: __bpf_prog_release (STB_LOCAL)
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
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f7c40)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff818f7c40-ffffffff818f7c89: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1a70)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff818b1a70-ffffffff818b1ab9: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81948c70)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff81948c70-ffffffff81948cb9: __bpf_prog_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_release(struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196a580)
Location: net/core/filter.c:1143
Inline: True
Direct callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff8196a580-ffffffff8196a5c9: __bpf_prog_release (STB_LOCAL)
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
