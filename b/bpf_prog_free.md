# Function: <code>bpf_prog_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811710e0)
Location: kernel/bpf/core.c:726
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__prog_put_common
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:__bpf_prog_release
```
**Symbols:**

```
ffffffff811710e0-ffffffff81171126: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117e7a0)
Location: kernel/bpf/core.c:1004
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - net/core/filter.c:__bpf_prog_release
```
**Symbols:**

```
ffffffff8117e7a0-ffffffff8117e7e6: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a3b0)
Location: kernel/bpf/core.c:1086
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - net/core/filter.c:__bpf_prog_release
```
**Symbols:**

```
ffffffff8118a3b0-ffffffff8118a3f6: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118cec0)
Location: kernel/bpf/core.c:1333
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff8118cec0-ffffffff8118cf0c: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119a9f0)
Location: kernel/bpf/core.c:1578
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff8119a9f0-ffffffff8119aa42: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b05c0)
Location: kernel/bpf/core.c:1745
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811b05c0-ffffffff811b060f: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bec40)
Location: kernel/bpf/core.c:1997
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811bec40-ffffffff811bec8f: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ceb80)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811ceb80-ffffffff811cebcf: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811db1a0)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811db1a0-ffffffff811db1ef: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8e90)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff811f8e90-ffffffff811f8efb: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7ed0)
Location: kernel/bpf/core.c:2148
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff811f7ed0-ffffffff811f7f3b: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8cb0)
Location: kernel/bpf/core.c:2273
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff811f8cb0-ffffffff811f8d1b: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122a340)
Location: kernel/bpf/core.c:2293
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff8122a340-ffffffff8122a3ab: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126be00)
Location: kernel/bpf/core.c:2581
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff8126be00-ffffffff8126be77: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c0fd0)
Location: kernel/bpf/core.c:2579
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff812c0fd0-ffffffff812c1047: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e7d40)
Location: kernel/bpf/core.c:2596
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff812e7d40-ffffffff812e7db7: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81306030)
Location: kernel/bpf/core.c:2776
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
**Symbols:**

```
ffffffff81306030-ffffffff813060a7: bpf_prog_free (STB_GLOBAL)
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
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025bbb8)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffff80001025bbb8-ffff80001025bc10: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c048f13c)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
c048f13c-c048f190: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000002ff9b0)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
c0000000002ff9b0-c0000000002ffa2c: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019a838)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffe00019a838-ffffffe00019a892: bpf_prog_free (STB_GLOBAL)
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
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d37c0)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811d37c0-ffffffff811d380f: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c6580)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811c6580-ffffffff811c65cf: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1590)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811d1590-ffffffff811d15df: bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811df880)
Location: kernel/bpf/core.c:1990
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
```
**Symbols:**

```
ffffffff811df880-ffffffff811df8cf: bpf_prog_free (STB_GLOBAL)
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
