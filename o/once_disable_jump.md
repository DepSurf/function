# Function: <code>once_disable_jump</code>

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
In lib/once.c (ffffffff81400dda)
Location: lib/once.c:21
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8144857a)
Location: lib/once.c:21
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff81466f6a)
Location: lib/once.c:21
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8146c42a)
Location: lib/once.c:21
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8149872a)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff814cd91a)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff814e1fea)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8150de9a)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8152bcea)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8158f6fa)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff815ac22a)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff815b6ee1)
Location: lib/once.c:25
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8161d491)
Location: lib/once.c:25
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff816eaf71)
Location: lib/once.c:25
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void once_disable_jump(struct static_key_true *key, struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff817db510)
Location: lib/once.c:25
Inline: False
Direct callers:
  - lib/once.c:__do_once_sleepable_done
  - lib/once.c:__do_once_done
```
**Symbols:**

```
ffffffff817db510-ffffffff817db595: once_disable_jump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void once_disable_jump(struct static_key_true *key, struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8181a780)
Location: lib/once.c:25
Inline: False
Direct callers:
  - lib/once.c:__do_once_sleepable_done
  - lib/once.c:__do_once_done
```
**Symbols:**

```
ffffffff8181a780-ffffffff8181a805: once_disable_jump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void once_disable_jump(struct static_key_true *key, struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/once.c (ffffffff8185fad0)
Location: lib/once.c:25
Inline: False
Direct callers:
  - lib/once.c:__do_once_sleepable_done
  - lib/once.c:__do_once_done
```
**Symbols:**

```
ffffffff8185fad0-ffffffff8185fb84: once_disable_jump (STB_LOCAL)
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
In lib/once.c (ffff800010637704)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (c07dd2f0)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (c0000000007dd70c)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffe000464904)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff815242ca)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff815145aa)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff8152035a)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
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
In lib/once.c (ffffffff81539cda)
Location: lib/once.c:22
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
