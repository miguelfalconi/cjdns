# You may redistribute this program and/or modify it under the terms of
# the GNU General Public License as published by the Free Software Foundation,
# either version 3 of the License, or (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.
set(Test_FILES
    AverageRoller_test.c
    Bits_test.c
    Base32_test.c
    Checksum_test.c
    Endian_test.c
    Hex_test.c
    Map_test.c
    Process_test.c
    UniqueName_test.c
    AddrTools_test.c
)
set(Test_LIBRARIES
    cjdns-util-events-libuv
    cjdmemory
    util
    cjdns-process
    cjdns-crypto-random
)
include(${CMAKE_SOURCE_DIR}/cmake/modules/Test.cmake)
