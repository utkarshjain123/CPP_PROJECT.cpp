#include <iostream>
#include <list>
#include <string>
#include <algorithm>

using namespace std;

int main() {
    list<string> linkedList;

    // Add strings to the linked list
    linkedList.push_back("bhakti");
    linkedList.push_back("vaishnavi");
    linkedList.push_back("vartika");
    linkedList.push_back("utkarsh");
    linkedList.push_back("bhakti");

    cout << "Original Linked List:" << endl;
    for (const string& word : linkedList) {
        cout << word << " ";
    }
    cout << endl;

    // Bubble sort to sort the linked list
    bool swapped;
    do {
        swapped = false;
        auto prev = linkedList.begin();
        auto current = prev;
        ++current;

        while (current != linkedList.end()) {
            if (*prev > *current) {
                iter_swap(prev, current);
                swapped = true;
            }
            ++prev;
            ++current;
        }
    } while (swapped);

    cout << "\nLinked List after Sorting:" << endl;
    for (const string& word : linkedList) {
        cout << word << " ";
    }
    cout << endl;

    list<string> repeatedWords;
    auto prev = linkedList.begin();
    auto current = prev;
    ++current;

    while (current != linkedList.end()) {
        if (*prev == *current) {
            repeatedWords.push_back(*prev);
        }
        ++prev;
        ++current;
    }

    if (!repeatedWords.empty()) {
        cout << "\nRepeated Words:" << endl;
        for (const string& word : repeatedWords) {
            cout << word << " ";
        }
        cout << endl;
    } else {
        cout << "\nNo repeated words found." << endl;
    }

    return 0;
}
#include <iostream>
#include <list>
#include <string>
#include <algorithm>

using namespace std;

int main() {
    list<string> linkedList;

    // Add strings to the linked list
    linkedList.push_back("bhakti");
    linkedList.push_back("vaishnavi");
    linkedList.push_back("vartika");
    linkedList.push_back("utkarsh");
    linkedList.push_back("bhakti");

    cout << "Original Linked List:" << endl;
    for (const string& word : linkedList) {
        cout << word << " ";
    }
    cout << endl;

    // Bubble sort to sort the linked list
    bool swapped;
    do {
        swapped = false;
        auto prev = linkedList.begin();
        auto current = prev;
        ++current;

        while (current != linkedList.end()) {
            if (*prev > *current) {
                iter_swap(prev, current);
                swapped = true;
            }
            ++prev;
            ++current;
        }
    } while (swapped);

    cout << "\nLinked List after Sorting:" << endl;
    for (const string& word : linkedList) {
        cout << word << " ";
    }
    cout << endl;

    list<string> repeatedWords;
    auto prev = linkedList.begin();
    auto current = prev;
    ++current;

    while (current != linkedList.end()) {
        if (*prev == *current) {
            repeatedWords.push_back(*prev);
        }
        ++prev;
        ++current;
    }

    if (!repeatedWords.empty()) {
        cout << "\nRepeated Words:" << endl;
        for (const string& word : repeatedWords) {
            cout << word << " ";
        }
        cout << endl;
    } else {
        cout << "\nNo repeated words found." << endl;
    }

    return 0;
}
#include <iostream>
#include <list>
#include <string>
#include <algorithm>

using namespace std;

int main() {
    list<string> linkedList;

    // Add strings to the linked list
    linkedList.push_back("bhakti");
    linkedList.push_back("vaishnavi");
    linkedList.push_back("vartika");
    linkedList.push_back("utkarsh");
    linkedList.push_back("bhakti");

    cout << "Original Linked List:" << endl;
    for (const string& word : linkedList) {
        cout << word << " ";
    }
    cout << endl;

    // Bubble sort to sort the linked list
    bool swapped;
    do {
        swapped = false;
        auto prev = linkedList.begin();
        auto current = prev;
        ++current;

        while (current != linkedList.end()) {
            if (*prev > *current) {
                iter_swap(prev, current);
                swapped = true;
            }
            ++prev;
            ++current;
        }
    } while (swapped);

    cout << "\nLinked List after Sorting:" << endl;
    for (const string& word : linkedList) {
        cout << word << " ";
    }
    cout << endl;

    list<string> repeatedWords;
    auto prev = linkedList.begin();
    auto current = prev;
    ++current;

    while (current != linkedList.end()) {
        if (*prev == *current) {
            repeatedWords.push_back(*prev);
        }
        ++prev;
        ++current;
    }

    if (!repeatedWords.empty()) {
        cout << "\nRepeated Words:" << endl;
        for (const string& word : repeatedWords) {
            cout << word << " ";
        }
        cout << endl;
    } else {
        cout << "\nNo repeated words found." << endl;
    }

    return 0;
}
