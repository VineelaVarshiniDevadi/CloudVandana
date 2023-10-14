import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.List;
public class ArrayShuffle {
    public static void main(String[] args) {
        // Create array
        Integer[] array = {1, 2, 3, 4, 5, 6, 7};
        // Convert array to list for shuffling
        List<Integer> list = new ArrayList<>(Arrays.asList(array));
        // Shuffle the list
        Collections.shuffle(list);
        // Convert the list back to array
        array = list.toArray(new Integer[0]);
        // Print the shuffled array
        System.out.println(Arrays.toString(array));
    }
}
