<script>
	import Selection from "./Selection.svelte";
	import LangSelection from "./LangSelection.svelte";
	import { currentLanguage } from '../stores/language.js';
    import { getTranslation } from '../lib/translations.js';

//	$: t = getTranslation($currentLanguage).welcome;
</script>

<!-- 

<svelte:head>
    <title>{t.title}</title>
</svelte:head>

<Selection
	option1={t.portfolio}
	option2={t.development}
	option3={t.tutoring}
/>

-->
