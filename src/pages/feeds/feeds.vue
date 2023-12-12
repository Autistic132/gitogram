<template>
    <div class="topline">
        <topline>
           <template #headline>
                <h1>Header</h1>
           </template> 
           <template #content>
            <h2> stories</h2>
           </template>
        </topline>
    </div>
</template>

<script>
import { topline  } from '../../components/topline';
import { icon } from "../../icons";
export default {
    name: 'feeds',
    components: {
        topline,
        icon
    }
}
</script>