<script>
  import theme from "./theme.json";

  const themeCss = `--primary-colour: ${theme.primary};\
  --secondary-colour: ${theme.secondary}; --text-colour: ${theme.text};`;
</script>

<div id="theme-container" style={themeCss}>
  <slot />
</div>
