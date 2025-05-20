# Function: <code>__proxy_share</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389c00)
Location: security/apparmor/label.c:91
Inline: False
Direct callers:
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff81389c00-ffffffff81389c8e: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c4830)
Location: security/apparmor/label.c:91
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813c4830-ffffffff813c48bd: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dbe80)
Location: security/apparmor/label.c:91
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813dbe80-ffffffff813dbf0d: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecf80)
Location: security/apparmor/label.c:92
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff813ecf80-ffffffff813ecfbb: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814145c0)
Location: security/apparmor/label.c:92
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814145c0-ffffffff81414604: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446960)
Location: security/apparmor/label.c:92
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81446960-ffffffff814469a7: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463a10)
Location: security/apparmor/label.c:92
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81463a10-ffffffff81463a57: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81490cc0)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81490cc0-ffffffff81490d0c: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aab70)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814aab70-ffffffff814aabbc: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81509460)
Location: security/apparmor/label.c:88
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_insert
Direct callers:
  - security/apparmor/label.c:aa_label_replace
```
**Symbols:**

```
ffffffff815091d0-ffffffff8150934c: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526190)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81526190-ffffffff81526236: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152bb20)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff8152bb20-ffffffff8152bbc6: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81589f00)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81589f00-ffffffff81589fa6: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162b0d0)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff8162b0d0-ffffffff8162b18f: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816df960)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff816df960-ffffffff816dfa1f: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81718fb0)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81718fb0-ffffffff8171906f: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81757a40)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81757a40-ffffffff81757aff: __proxy_share (STB_LOCAL)
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
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a1d10)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffff8000105a1d10-ffff8000105a1d90: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c075240c)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
c075240c-c0752474: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071cb20)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
c00000000071cb20-c00000000071cbc8: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec5c4)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffe0003ec5c4-ffffffe0003ec636: __proxy_share (STB_LOCAL)
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
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3150)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814a3150-ffffffff814a319c: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81493b70)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff81493b70-ffffffff81493bbc: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f1f0)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff8149f1f0-ffffffff8149f23c: __proxy_share (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __proxy_share(struct aa_label *old, struct aa_label *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7820)
Location: security/apparmor/label.c:88
Inline: False
Direct callers:
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:__label_insert
```
**Symbols:**

```
ffffffff814b7820-ffffffff814b786c: __proxy_share (STB_LOCAL)
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
