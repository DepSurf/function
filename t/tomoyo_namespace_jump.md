# Function: <code>tomoyo_namespace_jump</code>

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
In security/tomoyo/domain.c (ffffffff8136dca5)
Location: security/tomoyo/domain.c:486
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff813a3f55)
Location: security/tomoyo/domain.c:486
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff813baad5)
Location: security/tomoyo/domain.c:486
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff813d137f)
Location: security/tomoyo/domain.c:488
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff813f783f)
Location: security/tomoyo/domain.c:489
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81428814)
Location: security/tomoyo/domain.c:489
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff814450c4)
Location: security/tomoyo/domain.c:489
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81472d33)
Location: security/tomoyo/domain.c:501
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff8148cad3)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_namespace_jump(const char *domainname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e33c0)
Location: security/tomoyo/domain.c:505
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff814e33c0-ffffffff814e3416: tomoyo_namespace_jump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_namespace_jump(const char *domainname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff815007f0)
Location: security/tomoyo/domain.c:503
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff815007f0-ffffffff81500846: tomoyo_namespace_jump (STB_LOCAL)
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
In security/tomoyo/domain.c (ffffffff81507c73)
Location: security/tomoyo/domain.c:503
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81564e80)
Location: security/tomoyo/domain.c:503
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff8160065f)
Location: security/tomoyo/domain.c:503
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff816b159f)
Location: security/tomoyo/domain.c:503
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff816e9faf)
Location: security/tomoyo/domain.c:503
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81726cbf)
Location: security/tomoyo/domain.c:503
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffff80001057ffd4)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (c07324a8)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (c0000000006ed854)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffe0003d0cd4)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff814850b3)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81475ad3)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81481153)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
In security/tomoyo/domain.c (ffffffff81498cc3)
Location: security/tomoyo/domain.c:505
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
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
