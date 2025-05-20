# Function: <code>tomoyo_parse_envp</code>

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
In security/tomoyo/condition.c (ffffffff8136be83)
Location: security/tomoyo/condition.c:306
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813a208b)
Location: security/tomoyo/condition.c:306
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813b8c0b)
Location: security/tomoyo/condition.c:306
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813cf48f)
Location: security/tomoyo/condition.c:306
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813f593f)
Location: security/tomoyo/condition.c:307
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81426acf)
Location: security/tomoyo/condition.c:307
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff814431d3)
Location: security/tomoyo/condition.c:307
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81470e43)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8148abe3)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_parse_envp(char *left, char *right, struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814e19e0)
Location: security/tomoyo/condition.c:318
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff814e19e0-ffffffff814e1a7d: tomoyo_parse_envp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_parse_envp(char *left, char *right, struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814fed60)
Location: security/tomoyo/condition.c:318
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff814fed60-ffffffff814fedfd: tomoyo_parse_envp (STB_LOCAL)
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
In security/tomoyo/condition.c (ffffffff81506243)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff815630fb)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff815fe247)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff816af0c7)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff816e7ae7)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff817247f7)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffff80001057e1f0)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (c073066c)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (c0000000006ea55c)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffe0003cf354)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff814831c3)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81473be3)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8147f263)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81496d93)
Location: security/tomoyo/condition.c:318
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
