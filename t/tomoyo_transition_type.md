# Function: <code>tomoyo_transition_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8136e623)
Location: security/tomoyo/domain.c:331
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813a48fb)
Location: security/tomoyo/domain.c:331
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813bb47b)
Location: security/tomoyo/domain.c:331
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff813d1cc8)
Location: security/tomoyo/domain.c:333
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff813f81d8)
Location: security/tomoyo/domain.c:334
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814290f8)
Location: security/tomoyo/domain.c:334
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814459bc)
Location: security/tomoyo/domain.c:334
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff81473641)
Location: security/tomoyo/domain.c:339
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff8148d3e1)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum tomoyo_transition_type tomoyo_transition_type(const struct tomoyo_policy_namespace *ns, const struct tomoyo_path_info *domainname, const struct tomoyo_path_info *program);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e3420)
Location: security/tomoyo/domain.c:343
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff814e3420-ffffffff814e3516: tomoyo_transition_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum tomoyo_transition_type tomoyo_transition_type(const struct tomoyo_policy_namespace *ns, const struct tomoyo_path_info *domainname, const struct tomoyo_path_info *program);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81500850)
Location: security/tomoyo/domain.c:343
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff81500850-ffffffff81500946: tomoyo_transition_type (STB_LOCAL)
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
In security/tomoyo/domain.c (ffffffff81508632)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff815658c3)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff81601120)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff816b20b8)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff816eaa96)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff81727864)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (c0732c38)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (c0000000006ee44c)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffe0003d1170)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814859c1)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814763e1)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff81481a61)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814995f1)
Location: security/tomoyo/domain.c:343
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
</ul>
