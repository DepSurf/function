# Function: <code>smk_rule_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81364150)
Location: security/smack/smackfs.c:594
Inline: True
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff81364150-ffffffff813642a0: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8139a190)
Location: security/smack/smackfs.c:589
Inline: True
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff8139a190-ffffffff8139a2e0: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813b0e80)
Location: security/smack/smackfs.c:589
Inline: True
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff813b0e80-ffffffff813b0fd0: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813c7090)
Location: security/smack/smackfs.c:594
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff813c7090-ffffffff813c71e0: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813ed400)
Location: security/smack/smackfs.c:594
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff813ed400-ffffffff813ed550: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8141e490)
Location: security/smack/smackfs.c:594
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff8141e490-ffffffff8141e5d5: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8143ae00)
Location: security/smack/smackfs.c:594
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff8143ae00-ffffffff8143af45: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81468930)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff81468930-ffffffff81468a64: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81482710)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff81482710-ffffffff81482844: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814d85a0)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff814d85a0-ffffffff814d86d4: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814f5b10)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff814f5b10-ffffffff814f5c44: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814fc8c0)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff814fc8c0-ffffffff814fc9f4: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff815575b0)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff815575b0-ffffffff815576e4: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff815f1810)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff815f1810-ffffffff815f1952: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816a1ee0)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff816a1ee0-ffffffff816a2022: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816dacd0)
Location: security/smack/smackfs.c:565
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff816dacd0-ffffffff816dae12: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81717450)
Location: security/smack/smackfs.c:563
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff81717450-ffffffff81717592: smk_rule_show (STB_LOCAL)
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
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffff800010574128)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffff800010574128-ffff80001057428c: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0727318)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
c0727318-c072746c: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0000000006dca80)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
c0000000006dca80-c0000000006dcca8: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffe0003c7f30)
Location: security/smack/smackfs.c:564
Inline: True
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffe0003c7f30-ffffffe0003c806e: smk_rule_show (STB_LOCAL)
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
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8147acf0)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff8147acf0-ffffffff8147ae24: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146b710)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff8146b710-ffffffff8146b844: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81476d90)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff81476d90-ffffffff81476ec4: smk_rule_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smk_rule_show(struct seq_file *s, struct smack_rule *srp, int max);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8148e840)
Location: security/smack/smackfs.c:564
Inline: False
Direct callers:
  - security/smack/smackfs.c:load_self2_seq_show
  - security/smack/smackfs.c:load2_seq_show
  - security/smack/smackfs.c:load_self_seq_show
  - security/smack/smackfs.c:load_seq_show
```
**Symbols:**

```
ffffffff8148e840-ffffffff8148e974: smk_rule_show (STB_LOCAL)
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
