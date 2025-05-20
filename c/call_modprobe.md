# Function: <code>call_modprobe</code>

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
In kernel/kmod.c (ffffffff810968ad)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff81099c70)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff8109ec20)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff8109c3f3)
Location: kernel/kmod.c:96
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810b0fa0)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810b7dd5)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810c0ebd)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810c6fa6)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810d0076)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int call_modprobe(char *module_name, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff810d9e70)
Location: kernel/kmod.c:70
Inline: False
Direct callers:
  - kernel/kmod.c:__request_module
```
**Symbols:**

```
ffffffff810d9e70-ffffffff810d9f45: call_modprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int call_modprobe(char *module_name, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kmod.c (ffffffff810d5670)
Location: kernel/kmod.c:69
Inline: False
Direct callers:
  - kernel/kmod.c:__request_module
```
**Symbols:**

```
ffffffff810d5670-ffffffff810d5745: call_modprobe (STB_LOCAL)
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
In kernel/kmod.c (ffffffff810d741a)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810eacca)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff81105b09)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff8112b629)
Location: kernel/kmod.c:69
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/module/kmod.c (ffffffff811e179e)
Location: kernel/module/kmod.c:72
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
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
In kernel/module/kmod.c (ffffffff811f74dc)
Location: kernel/module/kmod.c:72
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
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
In kernel/kmod.c (ffff800010130604)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (c037fed4)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (c000000000179cd4)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffe0000e3aea)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810ca3f6)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810b8c06)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810c9926)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
In kernel/kmod.c (ffffffff810d1e66)
Location: kernel/kmod.c:70
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
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
