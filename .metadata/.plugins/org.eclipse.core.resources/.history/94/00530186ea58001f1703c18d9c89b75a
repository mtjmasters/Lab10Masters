package lab10Masters;

/*
 * testSelectionSort.java
 *
 * To change this template, choose Tools | Template Manager
 * and open the template in the editor.
 */

import static org.junit.Assert.*;
import org.junit.Test;

public class testSelectionSort {

    @Test
    public void test() {
        testPositive();
        testNegative();
        testMixed();
        testDuplicates();
    }

    public testSelectionSort() {
    }

    @Test
    public void testPositive() {
        int[] arr = new int[5];
        arr[0] = 8;
        arr[1] = 9;
        arr[2] = 7;
        arr[3] = 10;
        arr[4] = 2;

        int[] Sortedarr = new int[5];
        Sortedarr[0] = 2;
        Sortedarr[1] = 7;
        Sortedarr[2] = 8;
        Sortedarr[3] = 9;
        Sortedarr[4] = 10;

        SelectionSort sorter = new SelectionSort();
        assertArrayEquals(Sortedarr, sorter.basicSelectionSort(arr));
    }

    @Test
    public void testNegative() {
        int[] arr = new int[5];
        arr[0] = -8;
        arr[1] = -9;
        arr[2] = -7;
        arr[3] = -10;
        arr[4] = -2;

        int[] Sortedarr = new int[5];
        Sortedarr[0] = -10;
        Sortedarr[1] = -9;
        Sortedarr[2] = -8;
        Sortedarr[3] = -7;
        Sortedarr[4] = -2;

        SelectionSort sorter = new SelectionSort();
        assertArrayEquals(Sortedarr, sorter.basicSelectionSort(arr));
    }
    
    @Test
    public void testMixed() {
        int[] arr = new int[5];
        arr[0] = -8;
        arr[1] = 9;
        arr[2] = 0;
        arr[3] = -10;
        arr[4] = 2;

        int[] Sortedarr = new int[5];
        Sortedarr[0] = -10;
        Sortedarr[1] = -8;
        Sortedarr[2] = 0;
        Sortedarr[3] = 2;
        Sortedarr[4] = 9;

        SelectionSort sorter = new SelectionSort();
        assertArrayEquals(Sortedarr, sorter.basicSelectionSort(arr));
    }

    @Test
    public void testDuplicates() {
        int[] arr = new int[5];
        arr[0] = 2;
        arr[1] = 3;
        arr[2] = 3;
        arr[3] = 2;
        arr[4] = 1;

        int[] Sortedarr = new int[5];
        Sortedarr[0] = 1;
        Sortedarr[1] = 2;
        Sortedarr[2] = 2;
        Sortedarr[3] = 3;
        Sortedarr[4] = 3;

        SelectionSort sorter = new SelectionSort();
        assertArrayEquals(Sortedarr, sorter.basicSelectionSort(arr));
    }
}
