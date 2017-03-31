<script>
import Multiselect from 'vue-multiselect'

export default {
  name: 'vue-multiselect-locale-de',
  extends: Multiselect,
  props: {
    /**
     * String to show when pointing to an option
     * @default 'Press enter to select'
     * @type {String}
     */
    selectLabel: {
      type: String,
      default: 'Drücken Sie die Eingabetaste um das Element auszuwählen'
    },
    /**
     * String to show next to selected option
     * @default 'Selected'
     * @type {String}
    */
    selectedLabel: {
      type: String,
      default: 'Ausgewählt'
    },
    /**
     * String to show when pointing to an alredy selected option
     * @default 'Press enter to remove'
     * @type {String}
    */
    deselectLabel: {
      type: String,
      default: 'Drücken Sie die Eingabetaste um das Element abzuwählen'
    }
  }
}
</script>
