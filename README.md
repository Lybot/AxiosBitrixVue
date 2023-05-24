# AxiosBitrixVue
Axios v 1.4 for bitrix </br>
First way:
add this files to 'bitrix/js/ui/vue3/axios' <strong> AND </strong> 'bitrix/modules/ui/install/js/ui/vue3/axios'</br>
(Don't know why both paths are needed, but it won't work without it)
Use: import axios from 'ui.vue3.axios' </br>
Second:
Add this files to  local/js/{module}/axios </br>
Use: import axios from '{module}.axios' </br>
To update version of axios: </br>
1) download new ESM version from https://github.com/axios/axios/blob/release/dist/esm/axios.js </br>
2) run bitrix build </br>
